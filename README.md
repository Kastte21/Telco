# Telco Customer Churn Analysis

Análisis y predicción de abandono de clientes utilizando técnicas de ciencia de datos y aprendizaje automático.

## Descripción

Este proyecto tiene como objetivo analizar y predecir la probabilidad de abandono de clientes (churn) en una compañía de telecomunicaciones. Se utiliza un enfoque de machine learning para identificar patrones en los datos y proporcionar insights útiles para reducir el churn.

## Estructura del proyecto

- **`data/`**: Contiene los archivos de datos utilizados para el análisis.
- **`reports/`**: Resultados.
- **`README.md`**.

## Tecnologías utilizadas

- **Lenguaje**: Python
- **Bibliotecas principales**:
  - Pandas, NumPy: Manejo y análisis de datos.
  - Scikit-learn, XGBoost: Algoritmos de machine learning.
  - Matplotlib, Seaborn: Visualización de datos.
- **Herramientas**:
  - Git y GitHub para control de versiones.
  - Jupyter Notebooks para análisis interactivo.

## Procedimientos realizados

1. **Preparación de datos**: 
   - Limpieza y transformación de datos.
   - Manejo de valores nulos y variables categóricas.
2. **Análisis exploratorio de datos (EDA)**:
   - Visualización de patrones de comportamiento en los datos.
3. **Modelado**:
   - Entrenamiento de modelos (Regresión Logística, Random Forest, XGBoost, Ensemble).
   - Evaluación de modelos mediante métricas como precisión, recall y AUC.
4. **Balanceo de datos**:
   - Aplicación de técnicas como SMOTE y undersampling para manejar desequilibrios en las clases.

## Resultados

- **Mejor modelo**: Ensemble Undersampling (LogReg + RandomForest).
- **Métricas clave**:
  - Accuracy: `74.77%`
  - F1-Score: `64.35%`
  - Recall: `83.79%`
  - AUC-ROC: `86%`

## Cómo usar este proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Kastte21/Telco_Customer.git
   
2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
