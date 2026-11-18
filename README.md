# SentimientoAI – Aplicación de análisis de sentimientos

## 1. Descripción del proyecto

SentimientoAI es una aplicación móvil desarrollada con React Native y Expo, cuyo propósito es analizar textos escritos en español para identificar si expresan un sentimiento positivo o negativo.

La aplicación utiliza un modelo de Inteligencia Artificial basado en Regresión Logística y la técnica TF-IDF para procesar los textos y realizar predicciones. El modelo se ejecuta mediante un backend desarrollado con FastAPI, al cual se conecta la aplicación móvil mediante solicitudes HTTP.

El proyecto implementa la arquitectura MVVM (Model-View-ViewModel), con el objetivo de mantener una organización adecuada del código y separar la presentación, los datos y la lógica de la aplicación.
