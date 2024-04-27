# emotionDog

Reconocimiento de Emociones en Perros
El proyecto tiene como objetivo desarrollar un sistema de reconocimiento de emociones en perros utilizando técnicas de aprendizaje profundo, específicamente redes neuronales convolucionales (CNN). Se busca crear un modelo capaz de identificar las emociones principales en imágenes de perros, tales como felicidad, tristeza, ira y relajación.

Proceso del Proyecto
Preparación del Entorno y Descarga de Datos
Se comienza instalando las bibliotecas necesarias y descargando el conjunto de datos desde Kaggle utilizando la biblioteca opendatasets. Este conjunto de datos contiene imágenes etiquetadas con diferentes emociones de perros.

Exploración y Visualización de Datos
Se exploran las imágenes descargadas para comprender la estructura del conjunto de datos y visualizar algunas imágenes de muestra de cada emoción.

Preprocesamiento de Datos
Las imágenes se preprocesan para adaptarlas al formato adecuado para la entrada del modelo CNN. Esto incluye convertir las imágenes a escala de grises, redimensionarlas y normalizar sus valores de píxeles.

Entrenamiento del Modelo CNN
Se entrena un modelo de CNN utilizando TensorFlow y Keras. El modelo se entrena con las imágenes preprocesadas y las etiquetas de las emociones correspondientes. Se utiliza un conjunto de técnicas de aumento de datos para mejorar el rendimiento del modelo y evitar el sobreajuste.

Evaluación del Modelo
Se evalúa el rendimiento del modelo utilizando un conjunto de datos de prueba separado. Se calcula la precisión del modelo en la clasificación de las emociones de los perros.

Visualización de Resultados
Se visualizan los resultados del modelo, incluidas las métricas de precisión y pérdida a lo largo del entrenamiento, así como ejemplos de imágenes de prueba con sus emociones predichas.

Predicción en Nuevas Imágenes
Finalmente, se proporciona una función para realizar predicciones en nuevas imágenes de perros. El modelo entrenado se carga y se utiliza para predecir la emoción en la imagen proporcionada.

Objetivo Final
El objetivo final de este proyecto es desarrollar un sistema de reconocimiento de emociones en perros que pueda ser utilizado para diversas aplicaciones, como la detección de emociones en entornos de cuidado de mascotas o la creación de aplicaciones interactivas para propietarios de mascotas.

Este proyecto proporciona una base sólida para futuras investigaciones en el campo del reconocimiento de emociones en animales y puede servir como punto de partida para proyectos más avanzados en este tema.
