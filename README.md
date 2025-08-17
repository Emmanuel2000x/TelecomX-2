# 📊 Proyecto TelecomX -- Análisis y Modelado de Cancelación de Clientes

## 📌 Descripción

Este proyecto tiene como objetivo analizar los datos de clientes de
**TelecomX** y construir modelos predictivos que permitan anticipar la
**cancelación de servicios** (churn).

El flujo de trabajo incluye: 1. **Carga y exploración de datos** a
partir del archivo `Datos_Mod_TelecomX.csv`.\
2. **Limpieza y preparación** de la información:\
- Eliminación de valores nulos.\
- Codificación de variables categóricas.\
- Balanceo de clases con **SMOTE**.\
3. **Análisis exploratorio de datos (EDA):**\
- Boxplots, histogramas y distribuciones de variables.\
- Comparaciones entre clientes activos y cancelados.\
4. **Entrenamiento de modelos de Machine Learning:**\
- `LogisticRegression`\
- `SVC`\
- `RandomForestClassifier`\
- `XGBClassifier`\
5. **Optimización de hiperparámetros** con **GridSearchCV** y
**validación cruzada**.\
6. **Evaluación de desempeño** usando métricas de clasificación:\
- Exactitud (Accuracy)\
- Precisión (Precision)\
- Recall\
- F1-score\
- AUC-ROC\
7. **Interpretabilidad del modelo:**\
- Importancia de variables en Random Forest y XGBoost.\
- Coeficientes de Logistic Regression y SVC.\
- Visualización con gráficos de barras.

------------------------------------------------------------------------

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

## 📈 Resultados esperados

-   Identificación de las variables más relevantes para la cancelación.\
-   Comparación de modelos y selección del mejor estimador.\
-   Guardado de las configuraciones óptimas de cada modelo.\
-   Visualización de métricas y gráficos que facilitan la
    interpretación.

------------------------------------------------------------------------

## 🙌 Autor

Proyecto desarrollado por **Sergio Uribe** como parte de un ejercicio de
análisis y modelado de datos.
