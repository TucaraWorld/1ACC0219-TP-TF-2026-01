# 1ACC0219-TP-TF-2026-01
# 📊 Análisis de Sentimientos en Reseñas de Coursera

## 🎯 Objetivo
Aplicar técnicas de minería de textos y aprendizaje automático para analizar automáticamente las reseñas de cursos de Coursera, desarrollando un modelo de clasificación capaz de predecir el sentimiento (positivo, neutral o negativo) de los comentarios a partir de su contenido textual.  

El proyecto busca identificar patrones de satisfacción estudiantil mediante técnicas de Procesamiento de Lenguaje Natural (NLP) y clasificación supervisada.

---

## 👥 Integrantes

| Código | Integrante |
|---|---|
| U20231C416 | Carlos Fabian Mendoza Quispe |
| U202310474 | Patricia Lucia del Rosario Rojas Sanchez |
| U202317287 | Camila Adriana Ibarra Cabrera |
| U202315959 | Elias David Moncada Olivares |

---

## 📂 Dataset

Se utilizó el dataset **100k Coursera's Course Reviews Dataset**, disponible en Kaggle:

🔗 https://www.kaggle.com/datasets/septa97/100k-courseras-course-reviews-dataset

### Variables principales

| Variable | Descripción |
|---|---|
| `CourseId` | Identificador del curso |
| `Review` | Texto de la reseña del estudiante |
| `Label` | Valoración numérica del 1 al 5 |

El dataset contiene aproximadamente **140,000 reseñas** de cursos de Coursera y fue utilizado para realizar tareas de análisis exploratorio, procesamiento de lenguaje natural y clasificación de sentimientos.

---

## 📌 Conclusiones

- El análisis exploratorio permitió identificar un fuerte desbalance de clases, donde las reseñas positivas representaban aproximadamente el 91% del dataset.
- Se aplicó una técnica de undersampling para equilibrar las categorías de sentimiento y mejorar las condiciones de entrenamiento del modelo.
- Mediante técnicas de preprocesamiento con spaCy (lematización, eliminación de stopwords y puntuación), se obtuvo un conjunto de datos limpio y preparado para tareas de clasificación.
- Se propone utilizar el algoritmo **Multinomial Naive Bayes** junto con representación **TF-IDF**, debido a su eficiencia y buen desempeño en problemas de clasificación de texto.
- El proyecto demuestra la utilidad de las técnicas de NLP para analizar automáticamente la percepción de los estudiantes en plataformas de educación virtual.

---

## 📄 Licencia

Proyecto desarrollado con fines académicos para el curso de **Aplicaciones de Data Science** de la Universidad Peruana de Ciencias Aplicadas (UPC).
