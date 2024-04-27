# Reconocimiento de Emociones en Perros

Este proyecto tiene como objetivo desarrollar un sistema de reconocimiento de emociones en perros utilizando técnicas de aprendizaje profundo, específicamente redes neuronales convolucionales (CNN). Se busca crear un modelo capaz de identificar las emociones principales en imágenes de perros, tales como felicidad, tristeza, ira y relajación.

## Conjunto de Datos Utilizado

Para este proyecto, se utilizó el conjunto de datos "Dog Emotion" disponible en Kaggle. Este conjunto de datos contiene imágenes etiquetadas con diferentes emociones de perros, lo que lo hace ideal para el entrenamiento de modelos de reconocimiento de emociones en perros.

Puedes encontrar el conjunto de datos en el siguiente enlace: [Dog Emotion Dataset](https://www.kaggle.com/datasets/danielshanbalico/dog-emotion)

## Proceso del Proyecto

### Preparación del Entorno y Descarga de Datos

Se comienza instalando las bibliotecas necesarias y descargando el conjunto de datos desde Kaggle utilizando la biblioteca `opendatasets`. Este conjunto de datos contiene imágenes etiquetadas con diferentes emociones de perros.

### Exploración y Visualización de Datos

Se exploran las imágenes descargadas para comprender la estructura del conjunto de datos y visualizar algunas imágenes de muestra de cada emoción.

### Preprocesamiento de Datos

Las imágenes se preprocesan para adaptarlas al formato adecuado para la entrada del modelo CNN. Esto incluye convertir las imágenes a escala de grises, redimensionarlas y normalizar sus valores de píxeles.

### ¿Qué es un Modelo CNN?

Una red neuronal convolucional (CNN) es un tipo de red neuronal artificial especialmente adecuada para el procesamiento de imágenes. Las CNN están compuestas por múltiples capas, incluidas capas convolucionales, de agrupación y totalmente conectadas. Estas capas trabajan en conjunto para aprender automáticamente patrones y características de las imágenes, lo que hace que las CNN sean muy efectivas en tareas de reconocimiento de imágenes, como la clasificación de emociones en imágenes de perros.

### Entrenamiento del Modelo CNN

Se entrena un modelo de CNN utilizando TensorFlow y Keras. El modelo se entrena con las imágenes preprocesadas y las etiquetas de las emociones correspondientes. Se utiliza un conjunto de técnicas de aumento de datos para mejorar el rendimiento del modelo y evitar el sobreajuste.

### Evaluación del Modelo

Se evalúa el rendimiento del modelo utilizando un conjunto de datos de prueba separado. Se calcula la precisión del modelo en la clasificación de las emociones de los perros.

### Visualización de Resultados

Se visualizan los resultados del modelo, incluidas las métricas de precisión y pérdida a lo largo del entrenamiento, así como ejemplos de imágenes de prueba con sus emociones predichas.

### Predicción en Nuevas Imágenes

Finalmente, se proporciona una función para realizar predicciones en nuevas imágenes de perros. El modelo entrenado se carga y se utiliza para predecir la emoción en la imagen proporcionada.

### Implementación de la Interfaz Web

Después de guardar el modelo entrenado, se implementó una interfaz web utilizando HTML y JavaScript. El archivo `index.html` se abre localmente en un servidor web utilizando el comando `python -m http.server 8080`. Luego, se utiliza ngrok para crear un túnel HTTP y obtener un enlace público que se puede utilizar en diferentes dispositivos para interactuar con la aplicación de reconocimiento de emociones en perros.

## Objetivo Final

El objetivo final de este proyecto es desarrollar un sistema de reconocimiento de emociones en perros que pueda ser utilizado para diversas aplicaciones, como la detección de emociones en entornos de cuidado de mascotas o la creación de aplicaciones interactivas para propietarios de mascotas.
