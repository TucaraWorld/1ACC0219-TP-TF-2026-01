# 1ACC0219-TP-TF-2026-01
# Análisis de Sentimientos en Reseñas de Coursera

## Objetivo
Aplicar técnicas de minería de textos y aprendizaje automático para analizar 
automáticamente las reseñas de cursos de Coursera, desarrollando un modelo de 
clasificación capaz de predecir el sentimiento (positivo, neutral o negativo) 
de los comentarios a partir de su contenido textual, con el fin de identificar 
patrones de satisfacción estudiantil.

## Integrantes
- Carlos Fabian Mendoza Quispe (U20231C416)
- Patricia Lucia del Rosario Rojas Sanchez (U202310474)
- Camila Adriana Ibarra Cabrera (U202317287)
- Elias David Moncada Olivares (U202315959)

## Dataset
**100k Coursera's Course Reviews Dataset** — disponible en Kaggle.  
Contiene aproximadamente 140,000 reseñas de cursos de Coursera con las 
siguientes variables:
- `CourseId`: identificador del curso
- `Review`: texto de la reseña del estudiante
- `Label`: valoración numérica del 1 al 5

🔗 https://www.kaggle.com/datasets/septa97/100k-courseras-course-reviews-dataset

## Conclusiones
El análisis exploratorio permitió identificar un marcado desbalance en las 
clases de sentimiento, donde la clase positiva representa aproximadamente el 
91% del total de registros, lo cual requirió aplicar una técnica de 
undersampling para equilibrar las clases. Tras el preprocesamiento con spaCy 
(lematización, eliminación de stopwords y puntuación), se obtuvo un dataset 
limpio de ~105,777 reseñas en inglés listo para la etapa de modelado. Como 
propuesta de modelización, se plantea utilizar el algoritmo Naive Bayes con 
representación TF-IDF, el cual constituye un baseline sólido y ampliamente 
validado en tareas de clasificación de texto.

## Licencia
Este proyecto fue desarrollado con fines académicos para el curso de 
Aplicaciones de Data Science — Universidad Peruana de Ciencias Aplicadas (UPC).
