# Clasificador de Planes Megaline 📱🔍

Este proyecto tiene como objetivo desarrollar un modelo de machine learning para ayudar a la compañía móvil **Megaline** a recomendar uno de sus nuevos planes: `Smart` o `Ultra`. La predicción se basa en el comportamiento mensual de sus clientes.

## 🎯 Objetivo

Predecir con precisión cuál plan es más adecuado para un usuario según:
- Número de llamadas realizadas
- Duración total de llamadas
- Mensajes enviados
- Tráfico de datos móviles utilizado

## 🧪 Enfoque

Se entrenaron y compararon varios algoritmos de clasificación:
- Árbol de Decisión
- Bosque Aleatorio (Random Forest)
- Regresión Logística

Se usó validación cruzada, ajuste de hiperparámetros y una prueba de cordura para evaluar la solidez del modelo.

## ✅ Resultados

- 📈 **Mejor modelo**: Random Forest
- 🎯 **Exactitud alcanzada**: ~79.9%
- ✔️ Cumple con el umbral mínimo de precisión exigido por el negocio: 75%
- 🔎 **Modelo no sesgado**: Las predicciones mostraron una distribución razonable

## 🛠️ Tecnologías y librerías

- Python
- pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
