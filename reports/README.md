# Análisis de factores determinantes en costos del seguro médico

Este dashboard explora las variables clave que influyen en los cargos médicos de un grupo de 1338 asegurados, con foco en la interacción entre hábitos de vida (fumar), edad, índice de masa corporal (BMI) y región.

## Hallazgos principales

- **El tabaquismo** es el factor más impactante: los fumadores pagan en promedio $32,050, mientras que los no fumadores pagan solo $8,434 —casi cuatro veces menos.
- **La edad** tiene un efecto diferenciado: en no fumadores existe una correlación fuerte (r = 0.63) entre edad y costos; en fumadores, esta relación se diluye (r = 0.37), lo que sugiere que el tabaquismo domina sobre otros factores.
- **El BMI** amplifica el riesgo en fumadores: se observa una correlación muy alta (r = 0.81) entre BMI y cargos en este grupo, indicando que sobrepeso/obesidad combinado con tabaquismo genera un perfil de alto costo predecible.

## Distribución de gastos

De los 1338 asegurados analizados, 712 personas (53%) presentan cargos inferiores a $10,000. Sin embargo, un 11% (152 personas) supera los $30,000 en costos médicos, concentrándose mayoritariamente en el grupo de fumadores.

Este análisis demuestra que los costos no se explican por una sola variable, sino por combinaciones de riesgo. La herramienta permite filtrar por región, sexo y condición de fumador para explorar segmentos específicos.


## Dashboard interactivo

El entregable principal de este análisis es el dashboard desarrollado en Power BI, disponible en el archivo:

**Analisis_Seguros_Medicos_Dashboard.pbix**

El dashboard permite explorar de forma interactiva:
- Costos médicos por condición de fumador.
- Relación entre cargos, edad y BMI.
- Distribución de cargos y segmentación por región y sexo.

## Carpeta figures/

La subcarpeta `figures/` está reservada para visualizaciones estáticas (PNG/SVG) exportadas desde notebooks o utilizadas en informes técnicos.

En este proyecto, las visualizaciones finales se implementaron directamente en Power BI, por lo que no fue necesario generar figuras estáticas adicionales.

