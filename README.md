# Análisis de Costos del Seguro Médico

## Objetivo del proyecto

El objetivo de este proyecto es analizar los factores que influyen en los costos del seguro médico, identificando patrones y perfiles de riesgo asociados a variables demográficas y de estilo de vida, como la edad, el índice de masa corporal (BMI) y el hábito de fumar.

El análisis busca transformar datos históricos en información accionable, útil para comprender cómo la combinación de factores incrementa significativamente los costos médicos.

## Dataset

El análisis se basa en un conjunto de datos de seguros médicos compuesto por **1,338 registros**, donde cada observación representa a un asegurado individual.

El dataset incluye variables demográficas y de estilo de vida, entre ellas:
- Edad (`age`)
- Sexo (`sex`)
- Índice de masa corporal (`bmi`)
- Número de hijos (`children`)
- Región geográfica (`region`)
- Condición de fumador (`smoker`)
- Cargos médicos anuales (`charges`)

## Herramientas utilizadas

- **Python**: análisis exploratorio de datos y estadísticas descriptivas.
- **Pandas & NumPy**: manipulación y análisis de datos.
- **Matplotlib & Seaborn**: visualización exploratoria durante el EDA.
- **Power BI**: construcción de un dashboard interactivo para la visualización final de hallazgos.
- **Git & GitHub**: control de versiones y documentación del proyecto.

## Estructura del repositorio

Analisis-Seguros-Medicos/
│
├── data/
│ ├── raw/ # Datos originales sin modificar
│ ├── processed/ # No utilizado en este proyecto
│ └── external/ # Reservado para fuentes externas (no utilizado)
│
├── notebooks/ # Análisis exploratorio (EDA)
│ └── 01_exploracion_inicial.ipynb
│
├── reports/ # Resultados y conclusiones del proyecto
│ └── README.md
│
├── src/ # Código reutilizable (no utilizado en este proyecto)
│
├── models/ # Modelos entrenados (reservado para futuras extensiones)
│
├── .gitignore
└── README.md


## Visualizaciones

Las visualizaciones finales y el análisis interactivo fueron desarrollados en **Power BI**, complementando el análisis exploratorio realizado en Python.

El dashboard se encuentra en la carpeta `reports/` con el nombre:

**Analisis_Seguros_Medicos_Dashboard.pbix**

Este dashboard permite:
- Comparar costos promedio entre fumadores y no fumadores.
- Analizar la relación entre cargos médicos, edad y BMI.
- Explorar la distribución de costos por condición de fumador.
- Filtrar resultados por región, sexo y hábito de fumar.
