# Metodología

1. **Carga de datos**: Se carga `heart.csv` desde la carpeta `data/raw/` o desde un enlace público.
2. **EDA (Exploratory Data Analysis)**:
   - Revisión de tipos de datos y valores faltantes.
   - Estadísticas descriptivas por variable.
   - Visualizaciones: histogramas, boxplots, heatmap de correlación, countplots.
3. **Preprocesamiento**:
   - Manejo de valores faltantes (si aplica).
   - Codificación de variables categóricas.
   - Escalado de variables numéricas con StandardScaler.
   - División en set de entrenamiento y prueba (80/20).
4. **Modelado**:
   - Entrenar Regresión Logística como baseline.
   - Entrenar Random Forest Classifier.
   - Ajuste simple de hiperparámetros (si hay tiempo).
5. **Evaluación**:
   - Métricas: accuracy, precision, recall, f1-score, matriz de confusión.
   - Comparación entre modelos y discusión de trade-offs.
6. **Conclusiones y recomendaciones**:
   - Identificar variables más importantes y limitaciones del análisis.
