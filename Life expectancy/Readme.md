# Health Analytics: Análisis de la Esperanza de Vida

## Objetivo

El objetivo de este proyecto es analizar qué factores socioeconómicos y de salud pública influyen en la esperanza de vida al nacer en distintas regiones del mundo, y proporcionar recomendaciones clave para la Organización Mundial de la Salud (WHO) con el fin de mejorar los resultados de salud pública a nivel global.

## Herramientas

El análisis y modelado de datos se ha realizado utilizando Python y las siguientes librerías:

- Numpy: Para operaciones numéricas y manejo de arrays.
- Pandas: Para la manipulación y análisis de datos.
- Matplotlib, Plotly y Seaborn: Para la visualización de datos.
- Scikit-learn: Para el modelado de machine learning y clustering.
- XGBoost: Para el entrenamiento de modelos de predicción avanzados.
  
## Obtención y limpieza de los datos
Los datos utilizados en este proyecto han sido obtenidos de dos fuentes principales: *Our World in Data* y *World Bank*. Se ha realizado un proceso exhaustivo de limpieza de datos, que incluyó la normalización de nombres de países y el tratamiento de valores nulos.

## Habilidades y Técnicas

**Limpieza y Manipulación de Datos:**
- Normalización de nombres de países
- Tratamiento de valores nulos y otros métodos según la naturaleza de las variables.
- Uso de funciones avanzadas de Pandas para la transformación y manejo de los datos.
  
**Planteamiento del problema y Análisis Exploratorio de Datos:**

- Análisis exploratorio de datos (EDA).
- Formulación de hipótesis iniciales sobre los factores que podrían estar más correlacionados con la esperanza de vida. Identificar patrones, correlaciones y tendencias entre variables socioeconómicas y de salud pública. Análisis univariable por continente, país y región.
  
**Modelado de Clustering:**

- Implementación de un modelo de K-Means clustering, que agrupó los datos en 4 grupos en función de factores como el PIB per cápita, acceso a servicios de salud, y tasas de mortalidad, entre otros.
- Descripción de las características de los clusters y conclusiones.

**Modelos de *Machine Learning*:**

- Construcción de un modelo categórico para analizar los factores más relevantes que afectan a la esperanza de vida.
- Desarrollo de tres modelos de regresión para predecir la esperanza de vida, comenzando con un árbol de decisión, seguido por un random forest, y finalmente un XGBoost para mejorar la precisión de las predicciones.

**Presentación y comunicación de resultados:**

- Elaboración de un dashboard interactivo en *Looker Studio* que presenta los resultados clave y las recomendaciones de manera visual.
- Creación de una presentación que incluye visualizaciones claras y storytelling efectivo para comunicar los insights.

## Conclusiones Finales

Las conclusiones finales del análisis destacan qué factores tienen un mayor impacto en la esperanza de vida a nivel global y cómo las políticas públicas pueden influir en la mejora de estos indicadores. Además, se ofrecen recomendaciones específicas para la WHO para abordar estos factores en diversas regiones.

## Documentos Adjuntos:

- Memoria (PDF): Contiene un resumen detallado del proceso de análisis completo, así como la bibliografía complementaria.
- Presentación (PDF): Un resumen visual del proyecto, con los principales insights y conclusiones.
- Jupyter Notebooks (x3): Incluye todos los pasos del análisis, desde la limpieza de datos hasta la construcción de los modelos de machine learning y las conclusiones finales.
- Enlace al dashboard: https://lookerstudio.google.com/u/0/reporting/e1f2fcd9-5d3c-4b45-8054-485affe4e906/page/eAC4D
