# Analisis_de_sentimientos_instgram
Proyecto desarrollado para CRACK THE CODE Y UTP 

OBJETIVO

Analizar los comentarios de texto y clasificarlos en categorías de sentimiento, como positivo, negativo o neutro para la creación de un  DATASET
Entrenar un modelo de procesamiento de lenguaje natural con BERT a partir del DATASET con el propósito de clasificar los comentarios en categorías de sentimiento.
Analizar los comentarios con el modelo procesado, y obtener resultados 


PROBLEMÁTICA

El equipo deportivo UNIVERSITARIO DE DEPORTES “U” campeona en el torneo nacional (Perú) y automáticamente las páginas en la red social de Instagram generan publicaciones aduciendo el campeonato, generando tanto imágenes como textos alusivos a lo que sucedió la noche del del miércoles 08 de noviembre del 2023, se desea saber cuales son los sentimientos expresados en la referida plataforma, para lo cual se tomará como DATASET los comentarios de ambos equipos en ese día, y se analizará una publicación externa a los equipos rivales.


TECNOLOGÍAS USADAS

Python

NLTK (Natural Language Toolkit) , 
BERT(Bidirectional Encoder Representations from Transformers) , 
Transformers (Hugging Face Transformers) , 
Pandas ,
Matplotlib ,
Seaborn, 
PySpark ,
Emoji , 
TextBlob , 
WordCloud , 
TensorFlow , 
Google Colab


FUTURAS OPORTUNIDADES

Es posible implementar el análisis de sentimiento con modelos como BERT y emojis en el futuro. Actualmente, los modelos de procesamiento de lenguaje natural (NLP) están siendo desarrollados y mejorados continuamente, y existen enfoques que tienen en cuenta emojis y otros elementos de comunicación no verbal en el análisis de sentimiento.

Se debe considerar

Mejora del Modelo: Los modelos BERT  deberían de entrenarse o ajustarse para capturar mejor el significado de los emojis en el texto. Esto implicaría entrenar el modelo en un conjunto de datos etiquetado que incluya emojis y sus correspondientes etiquetas de sentimiento.

Preprocesamiento de Datos: El preprocesamiento de datos deberá incluir la extracción y codificación de emojis presentes en el texto. Esto puede realizarse utilizando bibliotecas de procesamiento de texto y emoji como se muestra en el código proporcionado.



ARCHIVOS USADOS:



SLIDE DE LA PRESENTACIÓN : https://docs.google.com/presentation/d/19NaOH-N25UZaBPYZvwsRW71bSmGAfSTFtdIxGV73NB0/edit?usp=sharing

COMENTARIOS PUBLICACIÓN SUNEDU : https://docs.google.com/spreadsheets/d/12iVIXMjufU-QOIeiVewQyeh-j0bwGSRi/edit?usp=drive_link&ouid=105441171632673518268&rtpof=true&sd=true

COMENTARIOS DE ENTRENAMIENTO PARA EL DATASET : https://docs.google.com/spreadsheets/d/15lsSaZgff0qZc2qbic2wsQMtP3_TjcwA/edit?usp=drive_link&ouid=105441171632673518268&rtpof=true&sd=true

DATASET DE ENTRENAMIENTO CON BERT  : https://drive.google.com/file/d/1yMG7PqrQb6x9NmuFg2P30cI267_qPgPr/view?usp=drive_link
