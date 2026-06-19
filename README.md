# tfg_dei_participedia
Análisis automatizado de DEI en casos de participación ciudadana de Participedia

## Estructura del proyecto

modules/          Módulos de Python con las funciones principales
  config.py       Conexión a la base de datos PostgreSQL
  patterns.py     Diccionario de categorías DEI (expresiones regulares)
  analysis.py     Funciones de detección y análisis de texto
  llm.py          Módulo de análisis con LLM
  visualization.py Funciones de visualización

pipeline.ipynb Pipeline principal — procesa los casos y sube resultados a SQL
analysis.ipynb Análisis y visualizaciones sobre los resultados 

README.md
