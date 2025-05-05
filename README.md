# Clasificador de Hojas Enfermas 🌿🦠

Este repositorio contiene un modelo de clasificación de hojas de plantas saludables y enfermas utilizando aprendizaje profundo. El modelo fue entrenado con imágenes del dataset [`plant_leaves`](https://www.tensorflow.org/datasets/catalog/plant_leaves) de TensorFlow, empleando la arquitectura MobileNetV2 para una clasificación eficiente en 22 clases.

## 🚀 Características

- Clasificación en **22 clases** (11 tipos de plantas en estados saludable y enfermo).
- Modelo entrenado con **MobileNetV2** preentrenado en ImageNet.
- App ligera en Vercel para predicción directa con imágenes cargadas por el usuario.

## 🏷️ Clases

Las clases se agrupan en dos categorías: `Saludable` y `Enferma` para cada tipo de planta:

**Mango**,
**Arjun**,
**Alstonia Scholaris**,
**Gauva**,
**Bael**
**Jamun**,
**Jatropha**,
**Pongamia Pinnata**,
**Basil**,
**Pomegranate**,
**Lemon**,
**Chinar**,

## 📊 Resultados

El modelo alcanzó una precisión superior al **90%** en los datos de prueba. Se utilizó una matriz de confusión, curvas ROC y métricas de clasificación para evaluar el rendimiento.

## 🧠 Modelo

- Base: `MobileNetV2`
- Entrenamiento en imágenes de 224x224
- Técnicas: aumento de datos, optimización con Keras Tuner

## 🌐 Despliegue

La aplicación web está desarrollada para facilitar el uso del modelo exportado. Se puede desplegar en plataformas como **Vercel** o **Streamlit**.

## ▶️ Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/eddelojeda/Clasificador_Hojas_Enfermas.git
   cd Clasificador_Hojas_Enfermas
   ```

2. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Corre los scripts de entrenamiento o lanza la app de predicción en `app/`.

## 📚 Dataset

- Dataset utilizado: [`plant_leaves`](https://www.tensorflow.org/datasets/catalog/plant_leaves)
- Fuente: TensorFlow Datasets (TFDS)

## ✏️ Autor

Desarrollado por [Eddel Ojeda](https://github.com/eddelojeda)
