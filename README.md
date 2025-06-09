# Proyecto: Clasificación del Nivel de Riesgo Crediticio en Clientes del Perú

## 1. Motivo del proyecto

Este proyecto nace del interés por aplicar ciencia de datos en un problema real de alta relevancia: la **clasificación del riesgo crediticio** de clientes a partir de variables demográficas, crediticias y socioeconómicas.

El objetivo principal fue poner en práctica habilidades clave en:

- **Análisis exploratorio de datos (EDA)**: identificar relaciones entre variables relevantes, detectar inconsistencias y patrones.
- **Ingeniería de características**: agrupar valores con baja representación y generar variables más robustas.
- **Preprocesamiento de datos**: limpieza, codificación, escalado y tratamiento del desbalance de clases.
- **Modelado predictivo**: aplicar modelos de clasificación supervisada para predecir el nivel de riesgo.
- **Evaluación de desempeño**: análisis de métricas como accuracy, f1-score, matriz de confusión y reporte de clasificación.

Como resultado, este proyecto contribuye a fortalecer competencias técnicas sobre un **caso real de segmentación de riesgo**, utilizando un dataset representativo del contexto peruano.

## 2. Resultados del proyecto

### Observaciones exploratorias destacadas

- **Relación directa entre los días de retraso de pago y el alto riesgo crediticio.**
- El nivel de riesgo bajo se concentra mayormente en viviendas **tipo OWN**.
- La presencia de garantías **no necesariamente indica menor riesgo**, como se observa en su distribución.

### Modelos entrenados:

- Logistic Regression  
- Gradient Boosting 
- Random Forest  
- XGBoost  
- Support Vector Machine

### Mejor rendimiento (modelo base tras validación cruzada y test set)

```text
Accuracy: 0.67
F1 Macro: 0.639

Classification Report:
              precision    recall  f1-score   support

    Bajo           0.68      0.83      0.75        23
    Medio          0.50      0.23      0.32        13
    Alto           0.75      1.00      0.86         6
