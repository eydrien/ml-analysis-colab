
# 🩺 Análisis de Enfermedades Cardíacas con Machine Learning

## 📘 Descripción del Proyecto
Este proyecto aplica **técnicas de Machine Learning** para predecir la presencia de **enfermedades cardíacas** en pacientes, utilizando el conjunto de datos público **Heart Disease Dataset** del repositorio UCI.  
El análisis se realiza completamente en **Google Colab**, una plataforma **SaaS (Software as a Service)** que permite ejecutar código en la nube sin necesidad de instalación local.

---

## 🎯 Objetivos

### Objetivo General
Realizar un análisis completo de datos reales sobre enfermedades cardíacas, aplicando algoritmos de Machine Learning para extraer patrones y generar predicciones relevantes.

### Objetivos Específicos
1. Utilizar Google Colab como plataforma SaaS para análisis de datos.  
2. Implementar técnicas de exploración y limpieza de datos (EDA).  
3. Aplicar algoritmos de Machine Learning (clasificación).  
4. Evaluar el rendimiento de los modelos y comparar sus resultados.  
5. Generar conclusiones y recomendaciones basadas en los datos.

---

## 🧠 Dataset Utilizado
**Fuente:** [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)  
**Versión usada:** Dataset limpio de Kaggle disponible [aquí](https://raw.githubusercontent.com/ChiragSahni/Data-Science-Heart-Disease/master/heart.csv).

**Variables principales:**
- `age`: Edad del paciente  
- `sex`: Sexo (1 = hombre, 0 = mujer)  
- `cp`: Tipo de dolor en el pecho  
- `trestbps`: Presión arterial en reposo  
- `chol`: Nivel de colesterol  
- `thalach`: Frecuencia cardíaca máxima  
- `target`: 1 = presencia de enfermedad, 0 = ausencia

---

## ⚙️ Metodología Aplicada

1. **Carga del dataset y exploración inicial (EDA)**  
   - Análisis de valores faltantes, distribuciones y correlaciones.  
   - Visualizaciones con Seaborn y Matplotlib.  

2. **Preprocesamiento**  
   - Normalización de variables numéricas.  
   - División del conjunto de datos (80% entrenamiento / 20% prueba).  

3. **Modelado con Machine Learning**  
   - **Regresión Logística** (modelo base interpretable).  
   - **Random Forest Classifier** (modelo avanzado).  

4. **Evaluación**  
   - Métricas: Accuracy, Precision, Recall, F1-score.  
   - Comparación de rendimiento entre modelos.  

5. **Conclusiones y recomendaciones**  
   - Interpretación de resultados y reflexión sobre el uso de Colab como SaaS.

---

## 🧩 Resultados Principales

| Modelo | Accuracy |
|:-------|:---------:|
| Regresión Logística | 0.85 |
| Random Forest | 0.90 |

**Conclusiones:**
- Las variables con mayor impacto fueron **frecuencia cardíaca máxima (thalach)** y **tipo de dolor en el pecho (cp)**.  
- El modelo de **Random Forest** mostró mejor rendimiento general.  
- El uso de Google Colab permitió realizar el análisis sin instalación local, demostrando las ventajas del enfoque SaaS.

---

## 🧰 Tecnologías y Librerías

- **Lenguaje:** Python 3  
- **Entorno SaaS:** Google Colab  
- **Librerías:** Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn, Plotly

---

## 🧾 Estructura del Repositorio

```
ml-analysis-colab/
├── README.md
├── notebooks/
│   ├── data_analysis.ipynb
│   └── exploratory_analysis.ipynb
├── data/
│   ├── raw/
│   │   └── heart.csv
│   ├── processed/
│   └── data_dictionary.md
├── results/
│   ├── visualizations/
│   ├── models/
│   └── reports/
├── docs/
│   ├── methodology.md
│   └── conclusions.md
└── video/
    └── presentation.mp4
```

---

## 🔗 Enlaces Importantes

- 📘 **Notebook en Google Colab:** [Abrir en Colab](https://colab.research.google.com/) *[](https://colab.research.google.com/drive/1CTDHwTKTGVnzbLcd9dcDwEjBoqgWmwqj?authuser=1#scrollTo=ML6R5RIWBU3u)*  
- 🎥 **Video de Sustentación:** **  

---

## 📌 Conclusiones Finales

- Se logró predecir correctamente la presencia de enfermedad cardíaca con un 90% de precisión.  
- Google Colab facilitó el desarrollo del análisis al operar completamente desde la nube.  
- El proyecto demuestra cómo el **SaaS** democratiza el acceso a herramientas avanzadas de análisis de datos.  
- Este enfoque puede escalarse para sistemas médicos predictivos reales.

---

## ✍️ Autor

**Adrián David González Romero**  
Auxiliar de Sistemas – Estudiante de Ingeniería de Sistemas y Computación  
Colombia, 2025  
