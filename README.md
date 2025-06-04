### 2. Metodología

El desarrollo del proyecto se llevó a cabo en un entorno de Google Colab, donde se trabajó con un dataset proporcionado por la empresa TelecomX. A continuación, se describen las principales etapas metodológicas:

1. **Carga de datos**  
   Se importó el conjunto de datos en formato CSV utilizando la biblioteca `pandas`. Se realizó una primera inspección de las columnas y tipos de datos.

2. **Limpieza y preprocesamiento**  
   - Eliminación de valores nulos o inconsistentes.
   - Conversión de variables categóricas a numéricas utilizando codificación `LabelEncoder` y `OneHotEncoder`.
   - Revisión de valores atípicos y errores en columnas numéricas.

3. **Análisis exploratorio de datos (EDA)**  
   - Se generaron gráficos de distribución, correlación y conteo para explorar patrones relevantes.
   - Se identificaron relaciones entre las características y el abandono de clientes (`churn`).

4. **Modelado predictivo**  
   - Se entrenaron modelos de clasificación utilizando algoritmos como `Logistic Regression`, `Random Forest` y `XGBoost`.
   - Se dividió el dataset en conjunto de entrenamiento y prueba (`train_test_split`).
   - Se evaluaron métricas como precisión, recall, f1-score y matriz de confusión.

5. **Visualización de resultados**  
   - Se usaron `matplotlib` y `seaborn` para visualizar desempeño de los modelos.
   - Se interpretaron las variables más importantes que influyen en la cancelación de servicios.

Esta metodología permitió identificar de manera eficiente los patrones que llevan a los clientes a abandonar la compañía, y contribuye a tomar decisiones estratégicas en áreas de retención y fidelización.

