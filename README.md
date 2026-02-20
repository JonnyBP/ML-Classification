# 🤖 Clasificación con Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python\&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter\&logoColor=white) ![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikit-learn\&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-Array-013243?logo=numpy\&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas\&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)

---

# 🎯 De los Datos a las Decisiones

> Implementación, explicación e interpretación de 8 algoritmos de clasificación usando Python y Scikit‑Learn.

Este documento muestra **cómo funcionan**, **cómo se entrenan** y **cómo interpretar los resultados** de los modelos más importantes de Machine Learning.

---

# 🌸 Dataset Utilizado

## Iris Dataset

Dataset clásico de Machine Learning.

Características:

* 150 muestras
* 4 variables numéricas
* 3 clases

Variables:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Clases:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Objetivo:

Predecir la especie de una flor.

---

# 🧠 Modelos Implementados

Este proyecto implementa 8 algoritmos fundamentales:

| Modelo              | Descripción                          |
| ------------------- | ------------------------------------ |
| Regresión Logística | Modelo probabilístico lineal         |
| Naive Bayes         | Clasificación basada en probabilidad |
| Árbol de Decisión   | Reglas lógicas tipo IF               |
| Random Forest       | Conjunto de árboles                  |
| Gradient Boosting   | Aprende de errores previos           |
| KNN                 | Clasificación por distancia          |
| SVM                 | Maximiza el margen entre clases      |
| Red Neuronal        | Simula el aprendizaje del cerebro    |

---

# ⚙️ Pipeline de Machine Learning: End-to-End

Flujo de trabajo para el desarrollo de modelos predictivos de clasificación.

---

## 🛠️ Fases del Proyecto

### 1. Ingesta y Análisis de Datos

* **Carga:** Extracción del dataset desde fuentes oficiales (Scikit-Learn).
* **EDA (Visualización):** Análisis exploratorio para identificar:
* **Distribución:** Sesgos y varianza de los datos.
* **Separabilidad:** Grado de solapamiento entre clases.
* **Patrones:** Relaciones lineales y no lineales ocultas.



### 2. Preprocesamiento y Split

Para garantizar que el modelo sea capaz de generalizar ante datos nuevos, dividimos el dataset:

| Conjunto | Propósito |
| --- | --- |
| **Entrenamiento** | Ajuste de parámetros y aprendizaje de patrones. |
| **Prueba** | Evaluación del rendimiento final (Blind test). |

> 💡 **Nota sobre Escalado:** Aplicamos `StandardScaler` para normalizar las características. Esto es crítico para algoritmos basados en distancias o gradientes como **SVM, KNN y Redes Neuronales**.

---

## 🚀 Implementación del Modelo

El núcleo se divide en tres comandos esenciales que gestionan el ciclo de vida del aprendizaje:

### Entrenamiento

El modelo ajusta sus pesos internos basándose en las etiquetas conocidas.

```python
modelo.fit(X_train, y_train)

```

### Inferencia

Generación de predicciones sobre datos que el modelo nunca ha visto.

```python
y_pred = modelo.predict(X_test)

```

---

## 📊 Métricas de Desempeño

La calidad del modelo no se define por un solo número. Utilizamos un enfoque multivariable:

* **Accuracy:** Porcentaje total de aciertos.
* **Matriz de Confusión:** Visualización de falsos positivos y negativos para detectar sesgos.
* **Reporte de Clasificación:** Análisis detallado de Precision, Recall y F1-Score.

---

# 📚 Referencias

Scikit‑Learn

[https://scikit-learn.org](https://scikit-learn.org)

UCI Machine Learning Repository

[https://archive.ics.uci.edu](https://archive.ics.uci.edu)

---

## 📚 Recursos para Seguir Aprendiendo

Si quieres profundizar en el funcionamiento visual de los clasificadores, te recomiendo estas herramientas:

* 🚀 **[TensorFlow Playground](https://playground.tensorflow.org/)**: Visualiza en tiempo real cómo aprende una red neuronal.
* 📸 **[Teachable Machine](https://teachablemachine.withgoogle.com/)**: Entrena modelos de clasificación de imágenes desde tu navegador.
* 📊 **[MLU-Explain](https://mlu-explain.github.io/)**: Explicaciones visuales y dinámicas sobre conceptos clave de Machine Learning.
* 🔬 **[GAN Lab](https://poloclub.github.io/ganlab/)**: Una herramienta interactiva para entender redes generativas.


## 📄 Licencia

Este proyecto es de uso académico y está basado en datos públicos.

---

## 👤 Autor

**Desarrollador:** Jonathan Brasales

**Proyecto:** Modelos de clasificación

**Contacto:** 
- 💼 LinkedIn: [jbrasales](https://www.linkedin.com/in/jbrasales/)
- 🐙 GitHub: [@JonnyBP](https://github.com/JonnyBP)


---

<div align="center">
  
**⭐ Si este proyecto te resulta útil, considera darle una estrella ⭐**

Hecho con ❤️ usando Python y Jupyter Notebook

</div>
