# ML-Examen3erIntentoCodingDojo
ML Examen 3er Intento Coding Dojo

Descripción
Instrucciones para examen
Objetivo: Este examen tiene como objetivo evaluar la capacidad del estudiante para limpiar, explorar, implementar y evaluar modelos de clasificación en un dataset de diabetes. Utilizaremos el «Diabetes Dataset» disponible en Kaggle. Los estudiantes deben demostrar habilidades prácticas en la manipulación de datos, creación de visualizaciones y modelado predictivo.

Contexto y Descripción del Dataset

El «Diabetes Dataset» contiene datos de salud de mujeres de ascendencia indígena Pima que viven cerca de Phoenix, Arizona, EE.UU. La tarea es predecir si un paciente tiene diabetes o no, basándose en ciertas medidas diagnósticas incluidas en el dataset.

Diccionario de Datos:

Pregnancies: Número de embarazos.
Glucose: Concentración de glucosa en plasma a las 2 horas en una prueba oral de tolerancia a la glucosa.
BloodPressure: Presión arterial diastólica (mm Hg).
SkinThickness: Espesor del pliegue cutáneo del tríceps (mm).
Insulin: Niveles séricos de insulina a las 2 horas (mu U/ml).
BMI: Índice de masa corporal (peso en kg / (altura en m)^2).
DiabetesPedigreeFunction: Función de pedigrí de diabetes.
Age: Edad (años).
Outcome: Variable objetivo (1: diabetes, 0: no diabetes).
Requisitos

Limpieza de Datos:
Identificación y eliminación de valores duplicados: Asegúrate de que no haya registros duplicados que puedan sesgar los resultados del análisis.
Verificación y ajuste de tipos de datos: Verifica que cada columna tenga el tipo de dato correcto (numérico o categórico) y ajusta si es necesario.
Corrección de inconsistencias en valores categóricos: Revisa las categorías de las variables y unifica aquellos valores que puedan estar escritos de diferentes maneras pero que representen lo mismo.
Manejo de valores faltantes adecuadamente: Identifica y maneja los valores faltantes utilizando técnicas apropiadas como la imputación de la mediana, media o moda, según corresponda.
Exploración de Datos:
Visualizaciones univariadas y multivariadas: Crea histogramas, gráficos de barras, diagramas de dispersión y mapas de calor para entender la distribución y las relaciones entre las variables.
Estadísticas descriptivas: Calcula medidas de tendencia central (media, mediana, moda) y de dispersión (rango, desviación estándar) para cada característica del dataset.
Implementación de Modelos:
Modelos de Clasificación: Implementa modelos de Random Forest y XGBoost.
Evaluación de Modelos: Evalúa los modelos utilizando métricas como accuracy, precision, recall, F1-score, y ROC-AUC.
Comparación de Rendimiento: Compara los resultados de ambos modelos y discute cuál es el más adecuado para este dataset.
Entrega

Los estudiantes deben entregar un archivo .ipynb comentado que incluya:

Proceso completo de limpieza y preprocesamiento de datos.
Visualizaciones y estadísticas descriptivas.
Implementación y evaluación de los modelos de clasificación.
Análisis comparativo del rendimiento de los modelos.
Además, el archivo debe subirse a GitHub con un tag de liberación (release tag) que permita identificar la entrega final.

Consideraciones Éticas y Tecnológicas

Consideraciones Éticas:

Transparencia y Reproducibilidad: Asegúrate de que todos los pasos del análisis sean claros y reproducibles. Otros investigadores deben poder seguir tus pasos y llegar a los mismos resultados.
Imparcialidad y Sesgo: Revisa si existen sesgos en los datos que puedan afectar la imparcialidad del modelo. Es importante que los modelos no discriminen injustamente entre diferentes grupos de datos.
Consideraciones Tecnológicas:

Herramientas Utilizadas: Utiliza herramientas estándar como Python, Jupyter Notebook, Pandas, Scikit-learn, Matplotlib y Seaborn.
Escalabilidad: Considera cómo las técnicas aplicadas podrían escalarse para manejar conjuntos de datos más grandes y complejos.
Optimización de Modelos: Aunque este examen no se enfoca en la optimización de hiperparámetros, se debe tener en cuenta para futuras implementaciones y mejorar el rendimiento de los modelos.
