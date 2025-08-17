# 📊 Proyecto TelecomX -- Análisis y Modelado de Cancelación de Clientes

## 📌 Descripción

Este proyecto tiene como objetivo analizar los datos de clientes de
**TelecomX** y construir modelos predictivos que permitan anticipar la
**cancelación de servicios** (churn).

El flujo de trabajo fue el siguente:

## 1. **Carga y exploración de datos**
A partir del archivo `Datos_Mod_TelecomX.csv` obtenido en el proyecto **TelecomX-Parte1**
## 2. **Limpieza y preparación** de la información:
- Eliminación de valores nulos.\
- Codificación de variables categóricas.
- Balanceo de clases con **SMOTE**.
## 3. **Análisis exploratorio de datos (EDA):**\
- Boxplots, histogramas y distribuciones de variables.
- Comparaciones entre clientes activos y cancelados.
## 4. **Entrenamiento de modelos de Machine Learning:**
- `LogisticRegression`
- `SVC`
- `RandomForestClassifier`
- `XGBClassifier`
## 5. **Optimización de hiperparámetros** con **GridSearchCV** y **validación cruzada**.
Para este proyecto las variables de entrenamiento fueron divididas en 5 grupos y la 
metrica sobre la que se entrenaron los modelos al haber balanceado  los resgistros fue
*f1*
## 6. **Evaluación de desempeño** usando métricas de clasificación:
- Exactitud (Accuracy)
- Precisión (Precision)
- Recall
- F1-score
## 7. **Interpretabilidad del modelo:**
Se realiza el análisis de las variables más relevantes para la predicción de la cancelación:
- Importancia de variables en Random Forest y XGBoost.
- Coeficientes de Logistic Regression y SVC.
- Visualización con gráficos de barras.
## **Conclusiones**
Despues del entrenamiento los modelos tubieron los siguientes resultados: 

| Model	                  | F1-score (Avg) Train | F1-score Test | Variación |
|-------------------------|----------------------|---------------|-----------|
| Logistic Regression     | 0.79                 | 0.71	         | -10.1%    |
| Support Vector Machine  | 0.72 	             | 0.60          | -16.6%    |
| Random Forest	          | 0.82                 | 0.73          | -10.9%   |
| XGBoost Classifier      | 0.82 	             | 0.73          | -10.9%   | 
------------------------------------------------------------------------
Los modelos Random forest y XGBoost fueron los que entregaron mejores resultados tanto en el 
entrenamiento como con los datos de prueba 
## 📂 Archivos del proyecto

-   **`TelecomX_2.ipynb`** → Notebook principal con todo el flujo de
    análisis, modelado y evaluación.\
-   **`Datos_Mod_TelecomX.csv`** → Dataset procesado de clientes de
    TelecomX.

------------------------------------------------------------------------

## ⚙️ Requisitos

Este proyecto fue desarrollado en **Python 3.x** y requiere las
siguientes librerías:

``` bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

------------------------------------------------------------------------

## ▶️ Ejecución

1.  Clona este repositorio o descarga los archivos.\
2.  Asegúrate de tener el archivo `Datos_Mod_TelecomX.csv` en la misma
    carpeta que el notebook.\
3.  Abre y ejecuta el notebook `TelecomX_2.ipynb` en Jupyter Notebook o
    Google Colab.

------------------------------------------------------------------------

## 🙌 Autor

Proyecto desarrollado por **Sergio Uribe** como parte de un ejercicio de
análisis y modelado de datos.
