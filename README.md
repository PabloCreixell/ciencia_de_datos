# ciencia_de_datos
Proyecto ciencia de datos UDP
# Examen de Ciencia de Datos para la Economía

Este repositorio contiene el trabajo desarrollado para el examen del curso de **Ciencia de Datos para la Economía**. El objetivo principal es analizar datos de encuestas de 1990 y realizar predicciones sobre los ingresos anuales de los encuestados utilizando técnicas de análisis de datos, visualización y reducción de dimensionalidad.

## **Estructura del Proyecto**
1. **`creixell_perez_examen.ipynb`**: Cuaderno de Jupyter que contiene el análisis completo, dividido en las siguientes secciones:
   - Análisis descriptivo de las variables.
   - Transformaciones y preparación de datos.
   - Aplicación de técnicas avanzadas como PCA (Análisis de Componentes Principales).

2. **`ingresos.txt`**: Dataset proporcionado para el análisis (no incluido en el repositorio por política de privacidad).

3. **Ramas**:
   - `main`: Contiene el análisis descriptivo y las visualizaciones iniciales.
   - `pca_analysis`: Incluye la implementación de PCA para reducción de dimensionalidad.

## **Objetivos**
- Realizar un análisis descriptivo y visualización de los datos.
- Preparar los datos mediante transformaciones e imputaciones en caso necesario.
- Aplicar la técnica de reducción de dimensionalidad PCA para identificar patrones en los datos.

## **Dataset**
El dataset original contiene 1,816 filas y 14 columnas con información relevante sobre los encuestados:
- **Variables principales**:
  - `estatura` (cm), `peso` (kg), `genero`, `edad`, `ingresos` (USD).
  - `educacion`, `educacion_madre`, `educacion_padre` (años).
  - `camina` y `ejercicio` (hábitos de actividad física).
  - `fumador`, `tenso`, `malhumorado` (hábitos y estados emocionales).

## **Herramientas Utilizadas**
- **Lenguaje:** Python
- **Bibliotecas:** 
  - `Pandas` y `NumPy` para manipulación de datos.
  - `Matplotlib` y `Seaborn` para visualización de datos.
  - `scikit-learn` para PCA y análisis avanzado.
- **Control de Versiones:**
  - Git y GitHub para registro del progreso.
