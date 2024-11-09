# Análisis de Rendimiento Académico de Estudiantes en Escuelas Portuguesas

Este proyecto analiza el rendimiento académico de estudiantes en dos escuelas portuguesas, basándose en el dataset público [**Student Performance Dataset**](https://archive.ics.uci.edu/dataset/320/student+performance) de UCI Machine Learning Repository. La información recopilada incluye datos demográficos, sociales y características relacionadas con la escuela, que se utilizarán para comprender mejor las variables que influyen en las calificaciones finales de los estudiantes en Matemáticas y Lengua Portuguesa.

### Contexto

Como en varios otros países (por ejemplo, Francia o Venezuela), se utiliza una escala de calificación de 20 puntos, donde 0 es la nota más baja y 20 es la nota perfecta. Durante el año escolar, los estudiantes son evaluados en tres períodos, y la última evaluación (G3 de la Tabla 1) corresponde a la calificación final.

Este estudio considera datos recogidos durante el año escolar 2005-2006 de dos escuelas públicas en la región de Alentejo, Portugal.

### Clasificación de Resultados de Evaluaciones

Los resultados de las evaluaciones a los estudiantes en Portugal y Francia se clasifican de la siguiente manera:

- **Excelente/Muy bueno (16-20)**
- **Bueno (14-15)**
- **Satisfactorio (12-13)**
- **Suficiente (10-11)**
- **Suspendido (0-9)**

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

