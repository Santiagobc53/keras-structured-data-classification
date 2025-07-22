# Clasificación de Datos Estructurados con Keras y TensorFlow

Este proyecto muestra cómo construir, entrenar y evaluar un modelo de clasificación para datos estructurados (tabulares), utilizando **TensorFlow**, **Keras** y el API de **tf.data** junto con capas de preprocesamiento (`preprocessing layers`). El laboratorio sigue la metodología práctica de Google Cloud (Qwiklabs) y está diseñado para ser ejecutado en entornos como Vertex AI Workbench, pero también es totalmente funcional en local.

## Objetivos del proyecto

- Cargar y analizar un archivo CSV con pandas.
- Procesar y mezclar datos tabulares usando tf.data.
- Utilizar capas de preprocesamiento de Keras para transformar los datos.
- Construir, entrenar y evaluar un modelo de clasificación binaria con Keras.
- Estandarizar un flujo profesional de experimentación en machine learning estructurado.

## Estructura del repositorio

keras-structured-data-classification/
│
├── data/ # Datos de entrada (CSV, muestras, etc.)
├── docs/ # Documentación adicional (imágenes, diagramas, notas)
├── notebooks/ # Notebooks de Jupyter (laboratorios, experimentos)
│ └── preprocessing_layers.ipynb
├── src/ # Código fuente (pipelines, módulos reutilizables)
│ └── preprocessing_pipeline.py
├── requirements.txt # Dependencias necesarias para reproducir el proyecto
└── README.md

markdown
Copiar
Editar

## Requisitos

- Python 3.8+
- TensorFlow 2.x
- scikit-learn
- pandas
- numpy

Instala las dependencias con:

```sh
pip install -r requirements.txt
Ejecución rápida
Descarga o clona el repositorio:

sh
Copiar
Editar
git clone https://github.com/Santiagobc53/keras-structured-data-classification.git
Abre el notebook principal:

notebooks/preprocessing_layers.ipynb

Sigue las instrucciones celda a celda y completa los ejercicios marcados con #TODO (o revisa la versión completa en el notebook si ya está resuelto).

Para ejecutar código adicional reutilizable, revisa la carpeta src/.

Créditos y fuente del laboratorio
Laboratorio adaptado de Qwiklabs y Google Cloud Platform: "Clasificación de datos estructurados mediante capas de preprocesamiento de Keras".

Proyecto desarrollado y documentado por Santiago Barrera como parte de su ruta de aprendizaje en inteligencia artificial y machine learning.

Licencia
Distribuido bajo licencia Apache 2.0, en línea con las políticas de los notebooks originales de Google.

¿Te sirvió este proyecto o tienes dudas?
Escríbeme o revisa mi perfil en GitHub para ver más proyectos de machine learning y ciencia de datos.

## Capturas del entorno real

### 1. Google Cloud Vertex AI Workbench
![Vertex AI Lab](docs/screenshots/GoogleCloud%20Vertex%20AI%20Lab.png)

### 2. JupyterLab en Google Cloud
![JupyterLab](docs/screenshots/google%20Cloud%20Jupyter%20Lab.png)
