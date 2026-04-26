# Modelos Estocásticos para la Toma de Decisiones

Repositorio de prácticas y proyectos desarrollados para la clase de Modelos Estocásticos.

### Índice de contenidos
- [Práctica 1: Procesos Estocásticos](#práctica-1-procesos-estocásticos)
- [Práctica 2: Cadenas de Markov](#práctica-2-cadenas-de-markov)
- [Práctica 3: Predicción del Laberinto](#práctica-3-predicción-del-laberinto)
- [Práctica 4: Distribución de Poisson](#práctica-4-distribución-de-poisson)
- [Práctica 5: Regresión Polinomial](#práctica-5-regresión-polinomial)
- [Proyecto: Predicción del Clima](#proyecto-predicción-del-clima)
- [Recursos y datos](#recursos-y-datos)
- [Cómo ejecutar los notebooks](#cómo-ejecutar-los-notebooks)
- [Estructura del repositorio](#estructura-del-repositorio)

---

### Práctica 1: Procesos Estocásticos
Implementación de ejemplos y simulaciones de procesos estocásticos, incluyendo análisis de rendimientos financieros y caminatas aleatorias.

[Ver carpeta tarea_01](./tarea_01/)

**Archivos:**
- `ejemplos_procesos_estocasticos.ipynb` — Implementación de gráficas de rendimiento financiero y simulación de procesos de Markov.
- `rendimiento_cetes.xlsx` — Datos históricos de rendimientos de CETES a 28 días (2003-2026).

---

### Práctica 2: Cadenas de Markov
Introducción y resolución de problemas de Cadenas de Markov con estados discretos para la predicción de condiciones climáticas.

[Ver carpeta tarea_02](./tarea_02/)

**Archivos:**
- `introduccion_a_las_cadenas_de_markov.ipynb` — Resolución de problemas de probabilidad de transición y matrices en dos pasos ($P^2$).

---

### Práctica 3: Predicción del Laberinto
Análisis y resolución de un laberinto mediante Cadenas de Markov, calculando tiempos esperados de absorción.

[Ver carpeta tarea_03](./tarea_03/)

**Archivos:**
- `prediccion_del_laberinto.ipynb` — Implementación del modelo de absorción para encontrar la salida del laberinto.

---

### Práctica 4: Distribución de Poisson
Resolución de problemas de probabilidad utilizando la distribución de Poisson para modelar eventos en intervalos de tiempo o espacio.

[Ver carpeta tarea_04](./tarea_04/)

**Archivos:**
- `distribucionPoisson.ipynb` — Cálculo de probabilidades para casos de una clínica veterinaria y un servicio de grúas.

---

### Práctica 5: Regresión Polinomial
Aplicación de modelos de regresión polinomial y múltiple para resolver problemas en diversas áreas como economía, salud, marketing y educación.

[Ver carpeta tarea_05](./tarea_05/)

**Archivos:**
- `regresionPolinomial.ipynb` — Implementación de modelos con `scikit-learn`, incluyendo análisis de sensibilidad y optimización de variables.

---

### Proyecto: Predicción del Clima
Desarrollo de un modelo predictivo para las condiciones climáticas en Seúl utilizando Cadenas de Markov.

[Ver carpeta proyecto](./proyecto/)

**Archivos:**
- `prediccion_del_clima.ipynb` — Análisis de datos, matriz de transición y predicción de estados futuros.
- `clima_seul.png` — Visualización de los resultados del modelo.

---

### Recursos y datos
- `rendimiento_cetes.xlsx`: Archivo de datos históricos para análisis financiero en la Práctica 1.

---

### Cómo ejecutar los notebooks
1. Clona este repositorio o descarga el ZIP.
2. Crea y activa un entorno (opcional pero recomendado), por ejemplo con conda o venv.
3. Instala Jupyter y las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib scikit-learn openpyxl
   ```
4. Inicia Jupyter Lab/Notebook:
   ```bash
   jupyter lab
   ```
5. Abre el notebook de interés dentro de la carpeta correspondiente y ejecuta las celdas.

---

### Estructura del repositorio
```text
ModelosEstocasticos/
├── tarea_01/                       # Procesos Estocásticos (CETES, caminata aleatoria)
├── tarea_02/                       # Cadenas de Markov (clima, matrices de transición)
├── tarea_03/                       # Predicción del laberinto (absorción)
├── tarea_04/                       # Distribución de Poisson
├── tarea_05/                       # Regresión Polinomial (múltiple y polinomial)
├── proyecto/                       # Proyecto Final (clima de Seúl)
└── README.md
```

### Notas
- Los nombres de archivos y carpetas están organizados para mantener la secuencia de la materia.
- Asegúrate de tener las librerías instaladas para evitar errores de importación al ejecutar las celdas de código.
- Si encuentras algún error o falta de dependencias, por favor abre un issue o envía un PR.

---
*Autor: Yael Gonzalez*
