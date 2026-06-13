# Pronóstico de Series Temporales con ARIMA 📈

Proyecto de análisis y pronóstico de series de tiempo aplicando el modelo **ARIMA**, desde la descomposición de la serie hasta la evaluación de las predicciones.

## 🎯 Objetivo

Modelar una serie temporal histórica para generar pronósticos, analizando sus componentes y seleccionando los parámetros óptimos del modelo ARIMA de forma fundamentada.

## 🔧 Metodología

1. **Descomposición de la serie temporal:** separación en sus componentes de tendencia, estacionalidad y residuo para entender el comportamiento de los datos.
2. **Análisis de estacionariedad:** aplicación del test de Dickey-Fuller para contrastar la hipótesis de estacionariedad de la serie.
3. **Identificación de parámetros (p, d, q):** uso de las funciones de autocorrelación (ACF) y autocorrelación parcial (PACF) para determinar los órdenes candidatos del modelo.
4. **Modelado con ARIMA:** ajuste de distintas configuraciones del modelo a los datos históricos y comparación visual de las predicciones.
5. **Evaluación de predicciones:** división en conjuntos de entrenamiento y prueba, y comparación del desempeño de los modelos mediante métricas de error.

## 🔍 Hallazgos clave

- La descomposición reveló una ligera tendencia a la baja en el período analizado.
- El análisis comparativo entre configuraciones ARIMA evidenció las limitaciones de ciertos modelos para capturar la estacionalidad, orientando la selección hacia la configuración más adecuada.

## 🛠️ Tecnologías

- Python
- Pandas / NumPy
- Statsmodels (ARIMA, descomposición, ACF/PACF, Dickey-Fuller)
- Matplotlib / Seaborn
- Jupyter Notebook

## 📁 Contenido del repositorio

- `serie_temporal_arima.ipynb` — Notebook con el desarrollo completo del análisis.

---

*Proyecto desarrollado en el marco del bootcamp Data Science con Python (Academia Desafío Latam).*
