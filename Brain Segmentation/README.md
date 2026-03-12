# 🧠 Neuroscience: 3D Brain Segmentation
**By Gladys Choque Ulloa** *Ph.D. Student in Computer Science | Statistics | Deep Learning | Machine Learning*

---

## 📌 Descripción del Proyecto
Este repositorio presenta un pipeline avanzado de **Deep Learning** para la segmentación automatizada de estructuras cerebrales. Utilizando arquitecturas **U-Net 3D**, el modelo aprende a delimitar regiones críticas en resonancias magnéticas (MRI), una tarea esencial para el diagnóstico médico y la investigación neurocientífica.

## 🔬 Metodología y Análisis
El análisis se divide en etapas clave diseñadas para la reproducibilidad y el rigor académico:

* **Exploración Multiaxial:** Visualización del volumen en planos Axial, Sagital y Coronal.
* **Preprocesamiento Estadístico:** Normalización de intensidades y redimensionamiento volumétrico (Resize 3D).
* **Modelado:** Implementación de una red neuronal convolucional (CNN) con estructura Encoder-Decoder.
* **Evaluación:** Generación de mapas de error comparando la predicción contra el estándar clínico (Target).

## 🛠️ Tecnologías
* **Backend:** Python 3.x, TensorFlow / Keras.
* **Neuroimagen:** Nibabel (lectura de NIfTI), Nilearn (visualización estadística).
* **Data Science:** NumPy, SciPy, Matplotlib.

## 📖 Uso Educativo
Este repositorio sirve como material de apoyo para workshops, clases, etc, en **Ciencia de Datos aplicada a la Salud**, demostrando cómo transformar datos médicos crudos en modelos predictivos funcionales.

## 📂 Dataset & Reproducibilidad
Para ejecutar este proyecto, se utiliza el conjunto de datos de neuroimagen disponible en Kaggle. Los archivos están en formato NIfTI, diseñados para estudios de segmentación volumétrica.

* **Fuente de Datos:** [Brain MRI Dataset en Kaggle](https://www.kaggle.com/datasets/unidpro/brain-cancer-dataset).
* **Instrucciones:** Descargar el archivo `archive.zip`, subirlo a su entorno de ejecución (o Google Colab) y ejecutar la celda de descompresión incluida en el notebook.

---
> *Transforming complex data into actionable medical insights.*
