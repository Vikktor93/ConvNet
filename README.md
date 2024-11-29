<p align="left">
   <img src="https://img.shields.io/badge/Status-En%20Desarrollo-green?style=plastic">
   <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python&logoColor=white"/>
   <img src="https://img.shields.io/badge/Jupyter-%23e58f1a.svg?style=plastic&logo=Jupyter&logoColor=white"/>

<img src="./assets/banner-CNN.png"/>

## Tarea 2 - Redes Convolucionales

Esta tarea compara el desempeño de un Perceptrón Multicapa (MLP) y una Red Neuronal Convolucional (CNN) en la tarea de clasificación binaria de imágenes de muffins y chihuahuas. El dataset utilizado para esta tarea se encuentra en [Kaggle](https://www.kaggle.com/code/surya12345/muffin-vs-chihuaha-image-classification). 

## Descripción

El objetivo principal es explorar y evaluar diferentes arquitecturas de redes neuronales en un problema de clasificación de imágenes. Para ello, se utilizan dos modelos principales:

- **Perceptrón Multicapa (MLP):** Modelo completamente conectado que trata las imágenes como un vector plano.
- **Red Neuronal Convolucional (CNN):** Modelo que aprovecha la estructura espacial de las imágenes para extraer características.

Se incluye un conjunto de datos con imágenes de muffins y chihuahuas, el cual es procesado y aumentado para mejorar el rendimiento de los modelos.

## Tecnologías Utilizadas
- Python 3.10.8
- TensorFlow/Keras: Para el diseño y entrenamiento de las redes neuronales.
- NumPy y Pandas: Manipulación y análisis de datos.
- Matplotlib: Visualización de métricas y datos.
- ImageDataGenerator: Para aumento de datos y preprocesamiento

## Estructura del Proyecto

La estructura del proyecto es la siguiente:
```
.
├── data/                     # Contiene las imágenes organizadas en carpetas (muffins/chihuahuas)
│   ├── train/                # Datos de entrenamiento
│   └── test/                 # Datos de prueba
├── 001-ConvNet.ipynb         # Cuaderno Jupyter utilizado para el análisis, entrenamiento y para los modelos
├── README.md                 # Descripción del proyecto
└── .gitattributes            # Configuración de Git para el manejo de archivos y texto

```