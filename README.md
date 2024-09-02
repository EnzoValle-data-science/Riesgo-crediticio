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
  - SVM obtuvo una precisión del 99.89% y un AUC del 99.89%, lo que indica un modelo casi perfecto en la predicción del riesgo de incumplimiento.
 

| **Resultados**                           | **Importancia de características**               |
|-------------------------------------------|--------------------------------------------------|
| ![Resultados SVM](https://github.com/user-attachments/assets/1777dd1a-94e4-4004-ba85-f1e3db6d032d) | ![Importancia de las caracteristicas SVM](https://github.com/user-attachments/assets/b801957b-55b0-4149-ba49-8da7ed3360c6) |

| **Matriz de Confusión**                   | **Curva ROC**                                    |
|-------------------------------------------|--------------------------------------------------|
| ![matriz de confusion SVM](https://github.com/user-attachments/assets/c2d2576f-fffa-459d-8792-2f37bace0cf2) | ![Curva roc SVM](https://github.com/user-attachments/assets/fe67079c-2c24-4d2e-aadd-99fb4b3af896) |


  
- **Dataset IFRS 9**:
  - El modelo Random Forest alcanzó una precisión del 98.76% y un AUC de 99.92%, mostrando gran capacidad de predicción en escenarios financieros.

| **Resultados**                           | **Importancia de características**               |
|-------------------------------------------|--------------------------------------------------|
| ![Resultados Random forest](https://github.com/user-attachments/assets/ea7e4bdc-9164-488d-bb8e-c9c76b9ccc4b) | ![Importancia de características random forest](https://github.com/user-attachments/assets/fe12b751-468e-4d26-a5e5-27def05bc840) |

| **Matriz de Confusión**                   | **Curva ROC**                                    |
|-------------------------------------------|--------------------------------------------------|
| ![Matriz de confusión random forest](https://github.com/user-attachments/assets/f7caeee6-7917-4d0d-afcb-3482f1daeef6) | ![Curva ROC random forest](https://github.com/user-attachments/assets/93ec9874-3c74-44b4-b127-114f018702e7) |


## Tecnologías
- **Python**: Utilizado para el análisis y modelado.
- **Librerías**:
  - pandas
  - scikit-learn
  - SMOTE
  - matplotlib
  - seaborn


## Datasets disponibles
https://drive.google.com/drive/folders/1bJ2oDYfe48wLIJKerDiB10GuCCkNIMIZ?usp=sharing

