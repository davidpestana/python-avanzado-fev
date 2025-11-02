## 🧠 Módulo 10 — Machine Learning y Procesamiento de Lenguaje Natural (NLP)

En este módulo exploramos cómo aplicar **técnicas de Machine Learning** al análisis de texto.
Aprenderás a limpiar, transformar, clasificar y agrupar textos mediante librerías como **NLTK** y **Scikit-learn**.

> 💡 Es el cierre del curso, donde integramos todo lo aprendido sobre estructuras, funciones, E/S y visualización
> para construir modelos de análisis de datos reales.

---

### 🎯 Objetivos de aprendizaje

* Conocer los fundamentos del procesamiento de texto (NLP).
* Utilizar **NLTK** para limpiar y normalizar texto.
* Aplicar **TF-IDF** y **Bag of Words** para convertir texto en números.
* Entrenar modelos **supervisados y no supervisados** de clasificación.
* Evaluar modelos y visualizar resultados con gráficos.
* Crear un laboratorio completo de clasificación y agrupamiento de textos.

---

### 📘 Contenido del módulo

| Notebook                             | Tema                    | Descripción                                                                                                                                           |
| ------------------------------------ | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **10.1 — NLTK básico**               | Introducción a NLTK     | Tokenización, stopwords y frecuencia de palabras. Aprenderás a dividir texto en tokens y limpiar datos.                                               |
| **10.2 — Preprocesado ML**           | Transformación de texto | Uso de `CountVectorizer` y `TfidfVectorizer` para convertir texto en matrices numéricas.                                                              |
| **10.3 — Clasificación supervisada** | Modelos supervisados    | Entrenamiento de modelos como **Naive Bayes** para clasificar textos en categorías.                                                                   |
| **10.4 — Clustering y comparación**  | Modelos no supervisados | Uso de **KMeans** y comparación frente a clasificadores supervisados.                                                                                 |
| **10.5 — Laboratorio final**         | Proyecto integrador     | Combina preprocesado, TF-IDF, clasificación (Naive Bayes) y clustering (KMeans) en un único flujo. Incluye análisis comparativo y ejercicios guiados. |

---

### 🧩 Reto final opcional

Crea un **análisis visual de similitud entre textos**:

1. Usa el vectorizador TF-IDF del laboratorio final.
2. Calcula la **similitud del coseno** entre todos los textos del dataset.
3. Representa los resultados con un **mapa de calor (`seaborn.heatmap`)**.
4. Identifica qué textos son más similares entre sí según su contenido.

💡 *Tip:* Puedes reutilizar las variables `vectorizador` y `X` del laboratorio 10.5.

---

### 📦 Librerías utilizadas

* `nltk` — Procesamiento básico del lenguaje natural.
* `scikit-learn` — Modelos ML, vectorización, métricas y clustering.
* `matplotlib` / `seaborn` — Visualización de resultados.
* `pandas` — Gestión y visualización de datasets.

---

### 🚀 Resultados esperados

Al finalizar este módulo podrás:

* Preprocesar texto en español (limpieza, tokenización y normalización).
* Entrenar modelos de clasificación supervisada (Naive Bayes).
* Aplicar algoritmos de clustering (KMeans).
* Visualizar métricas y patrones semánticos en texto.
* Desarrollar un flujo completo de análisis textual.
