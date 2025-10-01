# Predictor de Real Estate

## Descripción del problema
- El mercado inmobiliario es complejo para todo el mundo
- Listar una vivienda a un precio demasiado alto puede hacer que tarde meses en venderse; un precio demasiado bajo implica pérdidas para el propietario
- El objetivo del proyecto es construir un predictor de real estate que, a partir de datos de Redfin, permita estimar:  
  - El precio óptimo de una vivienda 
  - El tiempo esperado en el mercado en función de sus características
<br><br> 
## Objetivos principales
- Analizar datos del mercado inmobiliario en Texas
- Entrenar dos modelos de machine learning:  
  - Modelo 1: Predicción de precio de salida
  - Modelo 2: Predicción de días en el mercado en función del precio
- Desarrollar una aplicación interactiva en Python para poder utilizar el modelo desarrollado y en función de los parámetros seleccionados obtener una respuesta personalizada
<br><br> 
## Plan inicial de trabajo
- **Fase 1: Descarga de datos**  
  - Obtener datasets públicos de Redfin en formato CSV

- **Fase 2: Preparación de datos y análisis**  
  - Combinar distintos ficheros CSV en un único dataset
  - Limpiar valores nulos y estandarizar variables (fechas, precios, tamaño...)
  - Identificar variables relevantes para los modelos

- **Fase 4: Creación del modelos y evaluación**  
  - Modelo 1: Predicción del precio más adecuado
  - Modelo 2: Predicción de los días en el mercado en función del precio y otras variables  
  - Evaluar los modelos con métricas adecuadas 

- **Fase 6: Desarrollo de la aplicación**  
  - Implementar visualizaciones interactivas
  - Integrar un formulario para introducir dirección/atributos de la vivienda y obtener predicciones

<br><br> 
## Tecnologías previstas
- Lenguaje: Python (Google Colab principalmente)
- Librerías: Pandas, NumPy, XGBoost, Matplotlib, Plotly...
- Fuente de datos: Redfin (datasets descargables en CSV)
