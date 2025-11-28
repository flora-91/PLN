# Análisis de NLP: "Análisis de reseñas de cursos de Domestika"

### 

### 📌Descripción

El corpus está conformado por reseñas reales de alumnos publicadas en la plataforma Domestika, recopiladas manualmente en formato .txt. Incluye 26 documentos individuales (con una extensión de entre 80 y 200 palabras cada uno), escritos entre 2021 y 2025. Representan experiencias recientes de estudiantes en cursos online.



El corpus se encuentra acompañado de un archivo metadata.csv con la siguiente información: título, autor, fecha, categoría y cantidad aproximada de palabras.



### 🎯Objetivos del análisis

Elegí este corpus porque las reseñas de cursos online permiten analizar el Customer Experience educativo, es decir, cómo los alumnos perciben el aprendizaje y la figura del instructor. El objetivo es identificar qué factores están asociados a la satisfacción estudiantil: aplicabilidad práctica de los contenidos o valoración positiva del docente.

### 

### 🧠Hipótesis general

La satisfacción de los alumnos en cursos online aumenta cuando perciben que el aprendizaje es aplicable a su vida real y cuando valoran positivamente al instructor como figura de confianza.

### 

### 🔍Por qué es útil esta hipótesis

\- Integra dos componentes clave del Customer Experience educativo: valor práctico y confianza en el instructor.

\- Permite explicar mejor la satisfacción global considerando qué se aprende y quién enseña.

### 

### 

### 📊Hallazgos principales sobre el corpus

La mayoría de las reseñas presentan una tendencia positiva, aunque también aparecen opiniones neutrales y algunas negativas. Se observó un alto nivel de subjetividad: muchos usuarios escriben desde su experiencia emocional y personal, más que desde descripciones objetivas.

Esto confirma parcialmente la hipótesis de una recepción mayormente favorable.



### 🔄Comparación de métodos utilizados

* Las técnicas de Bag of Words (BoW) y TF-IDF fueron útiles para identificar palabras frecuentes y representativas del corpus. Estas técnicas resultan valiosas para clasificación o búsqueda de información.
* Los análisis de sentimiento con TextBlob y VADER ofrecieron una mirada complementaria al clasificar el tono emocional de los textos.
* En situaciones reales, BoW/TF-IDF es más útil para tareas estructuradas, mientras que embeddings o modelos semánticos avanzados permiten captar significados y matices que van más allá de las palabras aisladas.



### ⚠️Limitaciones encontradas

* TextBlob y VADER están entrenados principalmente para inglés, lo que introduce sesgos.
* No se capturan adecuadamente ironía, sarcasmo o referencias culturales.
* El uso de modelos entrenados en español, como BETO o modelos de Hugging Face, podría mejorar la precisión.



### 🚀Aplicaciones potenciales del análisis

* Este análisis es útil para marketing digital y experiencia de usuario, permitiendo monitorear opiniones de clientes y detectar rápidamente fortalezas y debilidades de un producto o servicio.
* Transforma texto libre en información cuantificable que facilita la toma de decisiones estratégicas.
* Futuras mejoras podrían incluir modelos de clasificación automática, análisis de temas (topic modeling) o dashboards interactivos para monitoreo en tiempo real.

### 

### 🛠️Técnicas de NLP aplicadas

* Preprocesamiento de texto: limpieza, tokenización, stopwords
* Bag of Words (BoW)
* TF-IDF
* Word Embeddings (spaCy)
* POS Tagging



### 💻Tecnologías utilizadas

* Python 3.x
* pandas, numpy
* scikit-learn
* spaCy
* matplotlib, seaborn
* collections
* string
* re



### 📂Instrucciones de reproducción

El notebook está completamente ejecutado y se encuentra en la carpeta "Notebook".



### 🔧Limitaciones y trabajo futuro

No se pudo realizar el análisis de sentimiento con TextBlob debido a problemas de clasificación, por lo que se intentó utilizar transformers sin buenos resultados.

### 

### 👩‍💻Autora

Florencia Lombardi

📧florencialombardi44@gmail.com

🗓️Trabajo Integrador - NLP - Fecha: 25/09/2025



