# Predictor de Real Estate

## Descripción del problema
- El mercado inmobiliario es complejo tanto para compradores como para vendedores
- Listar una vivienda a un precio demasiado alto puede hacer que tarde meses en venderse; un precio demasiado bajo supone pérdidas para el propietario
- El objetivo del proyecto es construir un **predictor de real estate** que, a partir de datos de Redfin (Texas), permita estimar:  
  - El **precio de salida** óptimo de una vivienda 
  - El **tiempo esperado en el mercado** en función de sus características



## Objetivos principales
- Analizar datos del mercado inmobiliario en Texas
- Crear visualizaciones interactivas que permitan entender cómo influyen distintas variables (ubicación, tamaño, habitaciones, baños, etc.)
- Entrenar **dos modelos de machine learning**:  
  - Modelo 1 → Predicción de precio de salida
  - Modelo 2 → Predicción de días en el mercado en función del precio
- Desarrollar un **dashboard interactivo en Python (Dash/Plotly)** para facilitar la exploración y la interpretación de los resultados


## Plan inicial de trabajo
- **Fase 1 – Descarga de datos**  
  - Obtener datasets públicos de Redfin en formato CSV

- **Fase 2 – Preparación de datos**  
  - Combinar distintos ficheros CSV en un único dataset
  - Limpiar valores nulos y estandarizar variables (fechas, precios, metros cuadrados, etc.)

- **Fase 3 – Análisis exploratorio (EDA)**  
  - Visualizar relaciones entre precio, tamaño, ubicación y días en mercado 
  - Identificar variables relevantes para los modelos

- **Fase 4 – Creación de modelos predictivos**  
  - Modelo 1: Predicción del **precio de salida** 
  - Modelo 2: Predicción de los **días en el mercado en función del precio y otras variables**  

- **Fase 5 – Validación y pruebas**  
  - Evaluar los modelos con métricas adecuadas (ej. MAE, precisión en clasificación de tiempo)
  - Ajustar hiperparámetros y comparar resultados  

- **Fase 6 – Desarrollo del dashboard**  
  - Implementar visualizaciones interactivas en Dash/Plotly
  - Integrar un formulario para introducir dirección/atributos de la vivienda y obtener predicciones

- **Fase 7 – Documentación y entrega**  
  - Redactar README con instrucciones y objetivos 
  - Preparar despliegue en la nube (Heroku, Render o similar)



## Tecnologías previstas
- **Lenguaje**: Python (Google Colab como entorno principal)
- **Librerías**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Plotly...
- **Fuente de datos**: Redfin (datasets descargables en CSV)
