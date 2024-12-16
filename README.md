# ciencia\_de\_datos

**Alumnos:** Pablo Creixell y Benjamín Pérez  
**Curso:** Ciencia de Datos para la Economía, UDP  

Este repositorio contiene el trabajo desarrollado para el examen del curso de **Ciencia de Datos para la Economía**.  
El objetivo principal es analizar datos de encuestas de 1990 y realizar predicciones sobre los ingresos anuales de los encuestados utilizando técnicas de análisis de datos, visualización y reducción de dimensionalidad.

---

# Estructura del Proyecto

1. **`creixell_perez_examen.ipynb`**  
   Cuaderno de Jupyter que contiene el análisis completo, dividido en las siguientes secciones:
   - Análisis descriptivo de las variables.
   - Transformaciones y preparación de datos.
   - Aplicación de técnicas avanzadas como PCA (Análisis de Componentes Principales).

2. **`ingresos.txt`**  
   Dataset proporcionado para el análisis (no incluido en el repositorio por política de privacidad).

3. **Ramas del proyecto:**
   - `main`: Contiene el análisis descriptivo y las visualizaciones iniciales.
   - `pca_analysis`: Incluye la implementación de PCA para reducción de dimensionalidad.

---

# Objetivos

- Realizar un análisis descriptivo y visualización de los datos.
- Preparar los datos mediante transformaciones e imputaciones en caso necesario.
- Aplicar la técnica de reducción de dimensionalidad **PCA** para identificar patrones en los datos.

---

# Dataset

El dataset original contiene **1.816 filas** y **14 columnas** con información relevante sobre los encuestados:

## Variables principales:
- **estatura**: en centímetros  
- **peso**: en kilogramos  
- **genero**  
- **edad**: en años  
- **ingresos**: en dólares  
- **educacion, educacion_madre, educacion_padre**: años de educación  
- **camina**: frecuencia semanal de caminatas al trabajo  
- **ejercicio**: días de la semana con actividad física  
- **fumador**: indicador binario (1 = sí, 2 = no)  
- **tenso, malhumorado**: días en dichos estados emocionales  

---

# Herramientas Utilizadas

- **Lenguaje:** Python  
- **Bibliotecas:**
  - `pandas` y `numpy` para manipulación de datos.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `scikit-learn` para PCA y análisis avanzado.

- **Control de Versiones:**
  - `Git` y `GitHub` para registro del progreso.

---

# Análisis Realizado

1. **Análisis descriptivo:**
   - Estadísticas básicas de las variables cuantitativas y categóricas.
   - Identificación de datos faltantes y tratamiento.

2. **Transformación y preparación:**
   - Imputación de valores faltantes.
   - Codificación de variables categóricas.
   - Escalamiento de variables numéricas.

3. **Reducción de dimensionalidad:**
   - Implementación del algoritmo **PCA** (Análisis de Componentes Principales).
   - Visualización de los primeros componentes principales para identificar patrones.

---

# Resultados

- Gráficos y análisis evidenciaron la influencia de variables como **educación** y **peso** sobre los **ingresos**.
- PCA permitió reducir la dimensionalidad del dataset manteniendo la varianza explicada en gran medida.

---

# Conclusión

Se completó exitosamente el análisis exploratorio y de reducción de dimensionalidad utilizando técnicas avanzadas en Python. La estructura del proyecto se gestionó eficientemente con **Git** y **GitHub**, cumpliendo con los objetivos del examen.
