# Proyecto Modelos y Simulación de Sistemas

## Integrantes 

* 1001686406 Hellen Jakeline Rubio Casas
    - Ingeniería de Sistemas 
* 1101760080 Héctor Andrés Güiza Ortegón 
    - Ingeniería de Sistemas

# Descripción del proyecto

Este proyecto busca predecir el nivel de desempeño (bajo, medio-bajo, medio-alto o alto) de estudiantes universitarios en las Pruebas Saber Pro de Colombia, basándose en información diversa de cada estudiante. La evaluación se realizará mediante la exactitud de las predicciones. 

## Enlace al proyecto en Kaggle

[Competencia en Kaggle: Pruebas Saber Pro Colombia](https://www.kaggle.com/competitions/udea-ai-4-eng-20251-pruebas-saber-pro-colombia)

## Procesamiento de datos

Para el procesamiento de datos, se utilizó la librería polars con el fin de aprovechar sus capacidades multicore frente a pandas. Se realizaron operaciones que facilitan el análisis posterior, como estandarizaciones, normalizaciones y se tomaron decisiones con respecto de los datos faltantes: se intentarán utilizar medidas que permitan su tratamiento.

## Creación del modelo

Para la creación del modelo usamos XGBoost con el fin de predecir el rendimiento de los estudiantes en categorías como ‘bajo’, ‘medio-bajo’, ‘medio-alto’ y ‘alto’, lo cual es un típico problema de clasificación multiclase abordado a través de un algoritmo de Machine Learning.

[Video explicativo](https://youtu.be/hPHWbsW19o8)
