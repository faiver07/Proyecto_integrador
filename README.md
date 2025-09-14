{
  "name": "Análisis de Datos con API de Yelp",
  "description": "Proyecto de análisis de información de restaurantes obtenida mediante la API de Yelp. Incluye un proceso completo de Exploración, Limpieza, Análisis y Visualización de datos.",
  "sections": {
    "Objetivo": "Identificar patrones en la oferta gastronómica y comportamiento de los consumidores usando datos obtenidos de Yelp.",
    "Etapas": [
      "Exploratory Data Analysis (EDA): inspección inicial, limpieza y detección de outliers.",
      "Extracción de Datos (API Yelp): conexión y descarga de datos actualizados.",
      "Análisis Final: integración de resultados, métricas descriptivas y visualizaciones."
    ],
    "Tecnologías": {
      "Lenguaje": "Python 3.10+",
      "Librerías": [
        "pandas",
        "numpy",
        "matplotlib",
        "seaborn",
        "plotly",
        "requests",
        "dotenv"
      ],
      "Entorno": "Jupyter Notebook"
    },
    "EstructuraRepositorio": [
      "Avance_1_EDA.ipynb - Análisis exploratorio de datos",
      "Avance_2_API_Yelp.ipynb - Extracción de información mediante la API de Yelp",
      "Avance_Analisis_Final.ipynb - Integración y conclusiones del análisis",
      "requirements.txt - Librerías necesarias",
      "README.md - Documentación del proyecto"
    ],
    "Instalación": [
      "git clone https://github.com/usuario/repositorio.git",
      "cd repositorio",
      "pip install -r requirements.txt",
      "Crear archivo .env con API_KEY=tu_api_key_aqui",
      "jupyter notebook"
    ],
    "Resultados": [
      "Identificación de categorías más populares de restaurantes",
      "Análisis de frecuencia de visitas y gasto promedio",
      "Visualizaciones de tendencias por ubicación, género y estrato socioeconómico",
      "Insights clave sobre la oferta gastronómica"
    ],
    "PróximosPasos": [
      "Ampliar dataset con más consultas a la API de Yelp",
      "Aplicar modelos de Machine Learning para segmentación de clientes",
      "Desplegar dashboard interactivo con Streamlit o Dash"
    ],
    "Autor": "Proyecto desarrollado por [Tu Nombre] como práctica de análisis de datos y uso de APIs en Python."
  }
}
