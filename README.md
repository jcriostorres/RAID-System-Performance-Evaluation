# RAID-System-Performance-Evaluation

# **Implementación y Evaluación de un Sistema RAID para Comparar su Rendimiento con un Disco Individual**

Este proyecto tiene como objetivo implementar y analizar sistemas RAID en diferentes configuraciones (RAID 0, RAID 1 y RAID 5) y comparar su rendimiento con un disco individual. El análisis fue realizado mediante pruebas de rendimiento y análisis estadísticos con herramientas como **ANOVA**, utilizando **Python** en un entorno de **notebook Jupyter**.

---

## **Objetivo**
El objetivo principal de este proyecto es:
1. **Implementar un sistema RAID** utilizando configuraciones RAID 0, RAID 1 y RAID 5.
2. **Comparar el rendimiento** del sistema RAID con un disco individual.
3. Evaluar el impacto de las configuraciones RAID en operaciones de lectura y escritura, tanto secuenciales como aleatorias.
4. Aplicar análisis estadísticos para determinar si las diferencias de rendimiento son significativas.

---

## **Descripción del Proyecto**
Este proyecto incluye las siguientes fases:

1. **Configuración del Entorno**:
   - Implementación de sistemas RAID utilizando herramientas y software de almacenamiento en un entorno Linux.
   - Configuración de un disco individual para servir como referencia.

2. **Medición del Rendimiento**:
   - Uso de herramientas como `KDiskMark` para realizar pruebas de lectura y escritura en cada configuración.
   - Captura de datos en un formato estructurado para análisis posterior.

3. **Análisis Estadístico**:
   - Aplicación de un análisis de varianza (**ANOVA**) para evaluar las diferencias de rendimiento entre las configuraciones.
   - Uso de gráficos como **boxplots**, **histogramas**, y **Q-Q plots** para la visualización de los residuos y validación de supuestos.

4. **Visualización de Resultados**:
   - Representación gráfica de las diferencias de rendimiento en diferentes configuraciones y tipos de pruebas.
   - Evaluación de la interacción entre los factores `Storage` y `Medicion`.

---

## **Tecnologías Utilizadas**
- **Python**: Lenguaje principal para análisis y visualización de datos.
- **Bibliotecas**:
  - `pandas`: Manipulación y limpieza de datos.
  - `matplotlib` y `seaborn`: Creación de gráficos y visualizaciones.
  - `statsmodels` y `scipy`: Análisis estadístico (ANOVA, pruebas de normalidad, etc.).
- **Jupyter Notebook**: Entorno para desarrollo interactivo.
- **KDiskMark**: Herramienta para realizar pruebas de rendimiento de almacenamiento.
