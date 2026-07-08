# Telecom-Analysis

Este repositorio contiene el análisis realizado del comportamiento de los clientes de la empresa de telecomunicaciones en Latinoamérica, ConnectaTel.

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Generar insights para el equipo de Estrategia e Integración de ConnectaTel Latinoamérica

Se trabajó con los siguientes datasets: 
`plans.csv` → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
`users.csv` → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
`usage.csv` → detalle del uso real de los servicios (llamadas y mensajes)

## 📂 Contenido del repositorio

- `notebooks/Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.


## 📘 Cómo reproducir el análisis

1. Abre `notebooks/Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

