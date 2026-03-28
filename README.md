# Modelos Estocásticos para la Toma de Decisiones

Este repositorio contiene los trabajos, tareas y proyectos realizados para la materia de **Modelos Estocásticos para la Toma de Decisiones**.

## Estructura del Proyecto

El repositorio se organiza por carpetas correspondientes a las tareas y ejemplos vistos en clase:

*   **tarea_01/**: Introducción a los procesos estocásticos.
    *   `ejemplos_procesos_estocasticos.ipynb`: Notebook con la implementación de gráficas de rendimiento financiero y simulación de procesos de Markov.
    *   `rendimiento_cetes.xlsx`: Datos históricos de rendimientos de CETES a 28 días (2003-2026).

## Contenido de las Tareas

### Tarea 1: Ejemplos de Procesos Estocásticos

En esta primera entrega se exploran dos conceptos fundamentales:

1.  **Análisis de Datos Reales (CETES):**
    *   Se procesan datos históricos de rendimientos de Certificados de la Tesorería (CETES) en México.
    *   Visualización de la serie de tiempo para observar el comportamiento estocástico de las tasas a través de los años.

2.  **Simulación de Procesos de Markov (Caminata Aleatoria):**
    *   Implementación de una caminata aleatoria simple con probabilidad $p=0.5$ de aumento y $q=0.5$ de disminución.
    *   Visualización de la evolución del proceso $X_n$ tras 10 pasos aleatorios partiendo de un estado inicial $X_0 = 0$.

## Requisitos

Para ejecutar los notebooks de este repositorio, se recomienda contar con un entorno de Python 3.x y las siguientes librerías:

*   `pandas`
*   `numpy`
*   `matplotlib`
*   `openpyxl` (para la lectura de archivos Excel)

Puedes instalarlas usando:

```bash
pip install pandas numpy matplotlib openpyxl
```

---
*Autor: Yael Gonzalez*
