<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL 1** </h1>

# <h1 align=center>**Machine Learning Operations (MLOps) - Sistema de Recomendación de Videojuegos**</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/67664604/217914153-1eb00e25-ac08-4dfa-aaf8-53c09038f082.png"  height=300>
</p>

¡Bienvenidos a mi proyecto de recomendación de videojuegos de Steam! 

<hr>  
### Descripción:

El proyecto esta enfocado en brindarle al usuario recomendaciones precisas de juegos que podrian interesarle en base a sus gustos personales, logrando asi un beneficio tanto para el usuario como para la propia empresa que brinda el servicio.
Para lograr este objetivo se ha trabajado con una base de datos de la plataforma Steam, pasando a través de una serie de procesos obteniendo una fuente de datos de calidad con el fin de alimentar a un programa capaz de encontrar las posibles coincidencias entre los juegos y el usuario.

### Rol Desarrollado

En este proyecto, asumí el rol de un Ingeniero de MLOps (Machine Learning Operations) aplicando tareas propias de un Data Engineering como tambien la de un especialista en aprendizaje automático.

## Procesos del proyecto:

### Transformaciones de Datos

Lectura y procesamiendo del dataset con un formato mas adecuado. Se realizaron alguns limpiezas de columnas innecesarias, algunos datos nulos, transformaciones de tipos de datos para facilitar la lectura de estos, entre otros pequeños procesos, en pos de un proceso mucho mas eficiente para el rendimiento del modelo.

### Feature Engineering

Se aplicó un análisis de sentimiento con NLP para categorizar reseñas de juegos en tres categorías: Positivo, Neutro y Negativo. Esto facilita el trabajo de los modelos de machine learning y el análisis de datos.

### Desarrollo de una API

Se utilizó el framework FastAPI para exponer los datos y las consultas a los usuarios, las cuales incluyen información sobre desarrolladores, usuarios, géneros y juegos recomendados.

### Deployment

El proyecto se puede implementar en servicios como Render o Railway para que la API esté disponible en línea.

### Modelo de Machine Learning

Se desarrolló un modelo de recomendación de juegos basado en la similitud del coseno. Los usuarios pueden obtener recomendaciones de juegos similares a uno que les guste.

## Video de Presentación

[https://youtu.be/DRz_EBaj6uI] - El video muestra las consultas propuestas en funcionamiento desde la API y una breve explicación del modelo de recomendación.

[https://p1-mlops.onrender.com/docs#/] - Enlace de mí MVP para consumo

¡Muchas gracias por visitar mi proyecto!

## Contenido del Repositorio
dataset/: Aquí se encuentran los tres archivos del dataset en formato csv ya procesados para poder ser consultados por las funciones de la API.

ETL-EDA: Este notebook muestra todos los procesos que realicé para conseguir un dataset mas optimizado.

main.py: Este es el archivo principal de la API FastAPI y posee las funciones que se utilizan para proporcionar los datos y recomendaciones a los usuarios.

ML.py: En este archivo se encuentra el código relacionado con el sistema de recomendación, que utiliza el algoritmo de similitud de coseno para recomendar juegos similares.

requirements.txt: El archivo que lista las bibliotecas de Python necesarias para ejecutar el proyecto.

## Tecnologías Utilizadas

### Lenguaje de Programación

- **Python**: Lenguaje principal utilizado para el desarrollo de este proyecto.
- **Jupyter Notebook**: Utilizado para la exploración de datos y desarrollo de código interactivo.

### Bibliotecas y Frameworks

- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **FastAPI**
- **TextBlob**

### Procesamiento de Lenguaje Natural (NLP)

- **TextBlob**

### Despliegue

- **Render**

### Bibliotecas de Machine Learning

- **Scikit-Learn**

### Almacenamiento de Datos

- **CSV**

### Datos de contacto

- **Nombre**: Santiago Eluney Paz
- **Correo Electrónico**: santiagopaz.ds@gmail.com
- **Github**: https://github.com/SantiagoPaz75
- **LinkedIn**: https://www.linkedin.com/in/santiago-eluney-paz-746599274/