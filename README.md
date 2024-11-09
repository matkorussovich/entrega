# Análisis de Rendimiento Académico de Estudiantes en Escuelas Portuguesas

Este proyecto analiza el rendimiento académico de estudiantes en dos escuelas portuguesas, basándose en el dataset público [**Student Performance Dataset**](https://archive.ics.uci.edu/dataset/320/student+performance) de UCI Machine Learning Repository. La información recopilada incluye datos demográficos, sociales y características relacionadas con la escuela, que se utilizarán para comprender mejor las variables que influyen en las calificaciones finales de los estudiantes en Matemáticas y Lengua Portuguesa.

## Estructura del proyecto

- **notebooks/**: Contiene el notebook principal `Student_Performance_Analysis.ipynb` donde se desarrolla el análisis de datos.
- **data/**: Carpeta destinada a almacenar los datasets `student-mat.csv` y `student-por.csv`.
- **README.md**: Descripción del proyecto y guía de uso.
- **environment/**: Carpeta que contiene el entorno virtual para reproducir el análisis.
- **requirements.txt**: Lista de dependencias necesarias para ejecutar el proyecto.

## Objetivos del Análisis

1. **Carga y limpieza del dataset**: Leer el dataset en un DataFrame de Pandas y preparar los datos para el análisis.
2. **Cálculo de métricas descriptivas**: Obtener estadísticas clave de las variables numéricas y categóricas.
3. **Visualización de datos**:
   - Descripción de variables categóricas y numéricas.
   - Análisis de correlaciones entre variables, especialmente entre factores demográficos y sociales y el rendimiento académico.
4. **Exploración de relaciones significativas**:
   - Identificar posibles patrones entre el rendimiento académico (notas) y factores como el tiempo de estudio, el estado de salud, y el consumo de alcohol.
5. **Informe final**: Generación de gráficos y conclusiones para explicar los resultados de una manera comprensible y accesible.

## Requisitos

Este proyecto requiere Python 3 y las librerías listadas en `requirements.txt`. Para instalar las dependencias, ejecute:

```bash
pip install -r requirements.txt
