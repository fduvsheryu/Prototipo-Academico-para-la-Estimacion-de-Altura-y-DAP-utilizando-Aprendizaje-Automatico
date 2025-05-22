# Prototipo-Academico-para-la-Estimacion-de-Altura-y-DAP-utilizando-Aprendizaje-Automatico

# 🌲 Predicción Dasométrica con IA | Dasometric Prediction with AI

**ES:** Sistema de predicción dasométrica con FastAPI, TensorFlow y OpenCV para estimar DAP y altura de árboles desde imágenes. Incluye entrenamiento de modelos, carga de datos desde CSV e imágenes, y permite ejecución local con acceso remoto mediante ngrok.  
**EN:** Dasometric prediction system using FastAPI, TensorFlow, and OpenCV to estimate DBH and tree height from images. Includes model training, CSV and image data loading, and enables local execution with remote access through ngrok.

---

## 📚 Descripción General | Overview

Este proyecto permite estimar automáticamente variables dasométricas (DAP y altura total) a partir de imágenes de árboles, usando técnicas de visión por computador e inteligencia artificial.  
This project estimates forest biometric variables (DBH and total height) from tree images using computer vision and AI techniques.

---

## ⚙️ Requisitos | Requirements

### 🖥️ Requisitos de Hardware (mínimos sugeridos):
- Procesador: Intel Core i5 o AMD Ryzen 5
- RAM: 8 GB
- Almacenamiento: 10 GB disponibles
- GPU (opcional pero recomendado): NVIDIA con soporte CUDA

### 🧪 Requisitos de Software:
- Python 3.8 o superior
- Ubuntu 20.04 o superior
- FastAPI
- TensorFlow
- OpenCV
- Uvicorn
- Pandas
- NumPy
- Ngrok

📁 Estructura del Proyecto

    app/api: backend en FastAPI

    data/raw: datos sin procesar (imágenes, CSVs)

    data/processed: datos preprocesados listos para entrenar

    models: modelos entrenados

    scripts: scripts de preprocesamiento y entrenamiento

    notebooks: notebooks de análisis

    images: gráficas y visualizaciones

    docs: documentación

🚀 Uso del sistema | How to Use

    Clona este repositorio en ubuntu / Clone this repository on Ubuntu

Ejecuta el servidor FastAPI / Run the FastAPI server:

     uvicorn main:app --reload

Abre tu navegador / Open your browser:

    http://127.0.0.1:8000/docs


📤 Predicción | Prediction

Puedes enviar imágenes al endpoint /predict y recibir las predicciones de DAP y altura.
🧾 Licencia | License

MIT License

Copyright (c) 2025 Rodrigo Pedraza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
✉️ Contacto | Contact

Rodrigo Pedraza
Correo institucional: rrpedrazar@ut.edu.co
Universidad del Tolima – Ingeniería Forestal
