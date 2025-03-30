# LSTM_Prediccion_Trafico_Colab
Predicción de tráfico reloj con redes neuronales LSTM. Cuaderno lista para Google Colab, con métricas, visualización y exportación de predicciones.
# 🚦 Predicción de Tráfico Vehicular con Redes Neuronales LSTM

Este repositorio contiene un cuaderno interactivo desarrollado en **Colaboración de Google** que aplica un modelo de **Lstm rojo neuronal** (Memoria Larga a Corto Plazo) para predecir el número de vehículos por hora en un segmento vial, utilizando datos históricos de tráfico.

---

## Objetivo

- Predecir la demanda de tráfico hora a parte de datos históricos.
- Utilizar modelos de aprendizaje profundo (LSTM) para series de tiempo.
- Evaluar el deseo del modelo con métricas estadísticas.
- Exportar las predicciones y visualizarlas gráficamente.

---

## Tecnologías utilizadas

- Pitón 3
- Colaboración de Google
- TensorFlow/Keras
- Scikit-aprende
- Pandas, NumPy, Matplotlib, Seaborn

---

## Requisitos del archivo de datos

El archivo CSV debe contener dos columnas:

- `fecha_hora`: en formato timestamp por hora (`YYYY-MM-DD HH:MM:SS`)
- `conteo_vehiculos`: número de vehículos registrados en esa hora

> Puedes usar este archivo de ejemplo:  
>  [tráfico_horario_simulado.csv](https://...)

---

## ¿como usar este proyecto?

1. **Clona o descarga este repositorio:**

```bash
clon git https://github.com/tuusuario/LSTM_Trafico.git
