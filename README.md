<h1 align="center">🏦 Bank Churn Prediction</h1>

<h3 align="center">Predicción de Abandono de Clientes Bancarios usando Machine Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/CatBoost-F5DE53?style=for-the-badge&logo=catboost&logoColor=black"/>
</p>

## 📌 Sobre el Proyecto

Este proyecto (Módulo 4 de Data Science en Henry) se centra en el modelado predictivo para identificar qué clientes tienen mayor probabilidad de abandonar una entidad bancaria (Churn). 

El objetivo de negocio es permitir que el banco tome medidas proactivas (retención, ofertas) basándose en las predicciones generadas por diferentes modelos de Machine Learning.

## 📁 Estructura del Repositorio

El proyecto ha sido estructurado siguiendo las mejores prácticas:

*   **`notebooks/`**: Contiene los cuadernos de Jupyter con el paso a paso:
    *   `1_EDA_RegresionLogistica.ipynb`: Análisis Exploratorio de Datos (EDA) y entrenamiento inicial con Regresión Logística.
    *   `2_GradientBoosting_Optimizacion.ipynb`: Implementación de modelos avanzados como Gradient Boosting y CatBoost, optimización de hiperparámetros.
    *   `3_AprendizajeNoSupervisado.ipynb`: Técnicas de clustering y reducción de dimensionalidad para encontrar patrones ocultos en los clientes.
*   **`docs/`**: Documentación del proyecto, reportes de evaluación en PDF y la presentación de negocio PPTX.
*   **`data/`**: (Ignorado en Git por tamaño/privacidad) Carpeta para el dataset original y el diccionario de variables.

## 🛠️ Metodología

1.  **Exploración y Limpieza (EDA):** Análisis de la distribución de variables (edad, salario estimado, balance), detección de valores nulos o atípicos, y codificación de variables categóricas (como país de origen).
2.  **Modelado - Supervisado:** Entrenamos y evaluamos múltiples modelos para predecir la variable objetivo:
    *   Logisitic Regression (Baseline)
    *   Gradient Boosting
    *   CatBoost
3.  **Modelado - No Supervisado:** Usamos técnicas de clustering para segmentar a los clientes basándonos en similitudes no obvias.
4.  **Evaluación:** Comparación de métricas clave como Accuracy, Precision, Recall y F1-Score, seleccionando el modelo con mejor capacidad para detectar a los verdaderos "fugados".

## 🚀 Cómo ejecutarlo

1. Clona este repositorio.
2. Asegúrate de tener instalado Python y las librerías necesarias (Pandas, Scikit-learn, Seaborn, Matplotlib, CatBoost).
3. (Opcional) Coloca tu dataset `Churn_Modelling.csv` en la carpeta `data/`.
4. Abre los cuadernos en `notebooks/` con Jupyter Lab o VS Code y ejecuta las celdas secuencialmente.

---
*Desarrollado por **Lourdes Diamela Alarcon** como parte de las entregas de Data Science.*
