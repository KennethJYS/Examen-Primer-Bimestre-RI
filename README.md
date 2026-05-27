# Examen Primer Bimestre — Recuperación de Información 2026-A

**Estudiante:** Kenneth Yar  
**Materia:** ICCD753 Recuperación de Información  

## Descripción
Sistema de recuperación de información que indexa reseñas de películas 
mediante embeddings y recupera documentos relevantes usando similitud coseno.

## Dataset
Rotten Tomatoes Movies and Critic Reviews Dataset  
Disponible en: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset

## Cómo ejecutar
1. Instalar dependencias:
   pip install -r requirements.txt
   
Si esta ejecutando en un entorno de Kaggle:
1. Ir a https://www.kaggle.com y crear una cuenta si no tiene una
2. Crear un nuevo notebook
3. Agregar el dataset desde:
   https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset
4. Subir el archivo YarKenneth_ex1bim_ir26a.ipynb
5. Ejecutar todas las celdas en orden

Si esta ejecutando en local:
1. Descargue el Dataset desde: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset
2. Colocar rotten_tomatoes_movies.csv y rotten_tomatoes_critic_reviews.csv en la misma carpeta del ipynb
3. Ejecutar todas las celdas

## Modelos utilizados
- all-MiniLM-L6-v2 (384 dimensiones)
- all-mpnet-base-v2 (768 dimensiones)
