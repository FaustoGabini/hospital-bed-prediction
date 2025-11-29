# Predicción de la Ocupación Diaria de Camas Hospitalarias

## Descripción general

Este proyecto desarrolla un sistema de _forecasting_ capaz de predecir la **ocupación diaria de camas hospitalarias** con un horizonte de **7 días**, utilizando modelos estadísticos, métodos basados en árboles y redes neuronales.

Incluye todo el _pipeline_:

-   procesamiento de datos crudos de hospitalizaciones,
-   construcción de series temporales,
-   ingeniería de variables exógenas (clima, calendario, etc.),
-   generación de ventanas,
-   entrenamiento, validación y comparación de modelos,
-   análisis de resultados y métricas.

El objetivo es **anticipar aumentos abruptos en la demanda hospitalaria** para mejorar la planificación de recursos críticos (personal, UTI, equipamiento).

## Modelos evaluados

-   Modelos ingenuos

    -   Naive
    -   Seasonal Naive
    -   Moving Average

-   Modelos estadisticos

    -   Ariama

-   Modelos basados en árboles

    -   Random Forest
    -   Gradient Boosting

-   Redes Neuronales
    -   MLP
    -   RNN

<p align="center"> <img src="pipeline.png" width="700px"> </p>

## Predicción vs serie real (mejor modelo):

<p align="center"> <img src="results/plots/RandomForest.png" width="600px"> </p>
