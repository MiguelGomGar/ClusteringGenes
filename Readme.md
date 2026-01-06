# Análisis de Expresión Génica: Clustering de Pacientes

Este proyecto aplica técnicas de **Machine Learning** no supervisado (PCA y K-Means) sobre un dataset de expresión génica para identificar y distinguir diferentes perfiles clínicos de pacientes.

## Descripción
El objetivo principal es agrupar a los pacientes basándose en sus similitudes genéticas.
- **Análisis Exploratorio:** Realizado en R para limpieza e inspección inicial de los datos.
- **Modelado:** Realizado en Python, aplicando PCA para reducción de dimensiones y K-Means para el clustering.

## Tecnologías
- **R** (tidyverse, ggplot2).
- **Python 3.9** (pandas, scikit-learn, seaborn, matplotlib).

## Resultados
Se determinó que el número óptimo de clusters es $k = 3$.
*([Heatmap](Results/heatmap_clusters.png))*

Como se observa en el gráfico, los pacientes se separan claramente en tres grupos con perfiles de expresión distintos.