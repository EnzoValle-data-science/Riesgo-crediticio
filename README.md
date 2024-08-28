# Predicción de Riesgo Crediticio

## Descripción
Este proyecto se centra en la predicción del riesgo de incumplimiento de crédito utilizando aprendizaje supervisado. Se trabajó con dos datasets:
1. **Lending Club Loan**: Un conjunto de datos públicos con información detallada sobre préstamos personales.
2. **Dataset compatible con IFRS 9**: Un conjunto de datos alineado con la normativa internacional IFRS 9, relevante para instituciones financieras.

Se implementaron modelos predictivos para calcular la probabilidad de incumplimiento (Probability of Default, PD) utilizando técnicas avanzadas de ciencia de datos.

## Objetivo
Comparar y evaluar diversos modelos de aprendizaje supervisado para predecir el riesgo crediticio utilizando los conjuntos de datos IFRS 9 y Lending Club Loan. Identificar el modelo con el mejor desempeño en estos conjuntos.

## Proceso

1. **Análisis Exploratorio de Datos (EDA)**: 
   - Limpieza de datos, análisis de características, y tratamiento de valores nulos.
   - Identificación de correlaciones y distribución de las variables.

2. **Transformación de Datos (ETL)**:
   - Uso de técnicas como SMOTE para balancear los datos desbalanceados.
   - Normalización y codificación de variables categóricas.

3. **Modelos Supervisados**:
   - **Regresión Logística**
   - **Árboles Binarios**
   - **Random Forest**
   - **Gradient Boosting**
   - **SVM**
   - **Deep Neural Networks (DNN)**

## Resultados
- **Dataset Lending Club**:
  - SVM obtuvo una precisión del 99.97% y un AUC del 99.97%, lo que indica un modelo casi perfecto en la predicción del riesgo de incumplimiento.
  
- **Dataset IFRS 9**:
  - El modelo Random Forest alcanzó una precisión del 98.76% y un AUC de 99.92%, mostrando gran capacidad de predicción en escenarios financieros.

## Tecnologías
- **Python**: Utilizado para el análisis y modelado.
- **Librerías**:
  - pandas
  - scikit-learn
  - SMOTE
  - matplotlib
  - seaborn


## Visualizaciones
Se generaron gráficos que muestran la importancia de las características en los modelos y las curvas ROC para medir el rendimiento de los clasificadores.


