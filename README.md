# Telco Customer Churn Analysis
Análisis y predicción de abandono de clientes utilizando técnicas de ciencia de datos y aprendizaje automático.

Descripción
Este proyecto tiene como objetivo analizar y predecir la probabilidad de abandono de clientes (churn) en una compañía de telecomunicaciones. Se utiliza un enfoque de machine learning para identificar patrones en los datos y proporcionar insights útiles para reducir el churn.

Estructura del proyecto
data/: Contiene los archivos de datos utilizados para el análisis.
notebooks/: Notebooks de Jupyter con los análisis y modelos.
eda.ipynb: Exploración de datos y análisis visual.
modeling.ipynb: Modelado y evaluación de modelos.
src/: Scripts de procesamiento y funciones auxiliares.
README.md: Este archivo, con la descripción del proyecto.
Tecnologías utilizadas
Lenguaje: Python
Bibliotecas principales:
Pandas, NumPy: Manejo y análisis de datos.
Scikit-learn, XGBoost: Algoritmos de machine learning.
Matplotlib, Seaborn: Visualización de datos.
Herramientas:
Git y GitHub para control de versiones.
Jupyter Notebooks para análisis interactivo.
Procedimientos realizados
Preparación de datos:
Limpieza y transformación de datos.
Manejo de valores nulos y variables categóricas.
Análisis exploratorio de datos (EDA):
Visualización de patrones de comportamiento en los datos.
Modelado:
Entrenamiento de modelos (Regresión Logística, Random Forest, XGBoost, Ensemble).
Evaluación de modelos mediante métricas como precisión, recall y AUC.
Balanceo de datos:
Aplicación de técnicas como SMOTE y undersampling para manejar desequilibrios en las clases.
Resultados
Incluye una breve descripción de los resultados obtenidos, como:

Mejor modelo: Ensemble (LogReg + RandomForest).
Métricas clave:
Accuracy: XX%
F1-Score: XX%
AUC-ROC: XX%
Cómo usar este proyecto
Clona este repositorio:
bash
Copiar código
git clone https://github.com/Kastte21/Telco_Customer.git
Instala las dependencias necesarias:
bash
Copiar código
pip install -r requirements.txt
Ejecuta los notebooks en la carpeta notebooks/.
