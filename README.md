# **Implementación y Evaluación de un Sistema RAID**

Este proyecto analiza el rendimiento de un sistema RAID comparado con un disco individual. El análisis fue realizado en un **notebook Jupyter** utilizando **Python**, con pruebas estadísticas basadas en **ANOVA** para evaluar la significancia de las diferencias de rendimiento.

---

## **Descripción del Proyecto**

El objetivo principal es:
1. Implementar configuraciones RAID (RAID 0, RAID 1 y RAID 5).
2. Comparar el rendimiento del sistema RAID frente a un disco único en operaciones de lectura/escritura secuenciales y aleatorias.
3. Analizar los resultados utilizando técnicas estadísticas (ANOVA) y visualizar los datos mediante gráficos.

---

## **Requisitos del Sistema**

Para ejecutar este proyecto, asegúrate de tener los siguientes requisitos mínimos:

- **Sistema Operativo**: Linux (Ubuntu recomendado) o Windows 10/11.
- **Python**: Versión 3.8 o superior.
- **Jupyter Notebook**.
- **RAM**: 8 GB o más.
- **Espacio en disco**: Al menos 5 GB libres.
- **KDiskMark**: Herramienta para realizar pruebas de rendimiento de almacenamiento.

---

## **Dependencias**

El análisis utiliza las siguientes bibliotecas de Python:

- `pandas`: Para la manipulación de datos.
- `numpy`: Para cálculos matemáticos.
- `matplotlib`: Para la visualización de datos.
- `seaborn`: Para gráficos avanzados.
- `scipy`: Para pruebas estadísticas (Shapiro-Wilk, ANOVA).
- `statsmodels`: Para el análisis ANOVA y modelos lineales.

---

## **Instalación**

Sigue estos pasos para instalar las dependencias y ejecutar el proyecto:

### **1. Clona el repositorio**
```bash
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
cd nombre-del-repositorio

