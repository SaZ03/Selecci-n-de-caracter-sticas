# Selección de características

# Selección de Características - Vino Tinto

El objetivo de este proyecto es generar un **modelo de regresión lineal múltiple** que contenga solamente las variables seleccionadas mediante un proceso de **selección hacia adelante (forward selection)** y un proceso de **eliminación hacia atrás (backward elimination)**, con el fin de predecir la calidad de vinos tintos.

## Base de datos

Se trabajó con la base de datos **“Vino Tinto.csv”**, que contiene **1,599 observaciones** con **11 variables predictoras** y una variable de salida (**calidad**).  
Los datos provienen del **UCI Machine Learning Repository** y fueron originalmente reportados en una publicación científica para la revista *Decision Support Systems*.

### Variables de la base de datos
- **acidezFija**: Gramos de ácido tartárico por decímetro cúbico.  
- **acidezVolatil**: Gramos de ácido acético por decímetro cúbico.  
- **acidoCitrico**: Gramos de ácido cítrico por decímetro cúbico.  
- **azucarResidual**: Gramos de azúcar por decímetro cúbico.  
- **cloruros**: Gramos de cloruro de sodio por decímetro cúbico.  
- **dioxidoAzufreLibre**: Miligramos de dióxido de azufre libre por decímetro cúbico.  
- **dioxidoAzufreTotal**: Miligramos de dióxido de azufre total por decímetro cúbico.  
- **densidad**: Medida en gramos por centímetro cúbico.  
- **pH**: Nivel de pH del vino.  
- **sulfatos**: Gramos de sulfato de potasio por decímetro cúbico.  
- **alcohol**: Volumen porcentual de alcohol en el vino.  
- **calidad**: Mediana de la calidad otorgada por al menos tres catadores (escala de 0 a 10). *(Variable objetivo)*  

## Objetivo de la actividad

Implementar la metodología de selección hacia adelante y hacia atrás para identificar el conjunto óptimo de variables predictoras en un **modelo de regresión lineal**, evaluando su desempeño mediante la métrica **R²** y utilizando **validación cruzada**.

## Archivos disponibles
- 📘 **Reporte en Jupyter Notebook** → [Selección de Características.ipynb](./Selección%20de%20Características.ipynb)  
- 📄 **Reporte en PDF** → [Selección de Características.pdf](./Selección%20de%20Características.pdf)  
- 🌐 **Reporte en HTML** → [Selección de Características.html](./Selección%20de%20Características.html)  
- 🗂️ **Base de datos** → [Vino Tinto.csv](./Vino%20Tinto.csv)  
