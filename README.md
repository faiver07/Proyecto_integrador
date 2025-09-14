# 📊 Análisis de Datos con API de Yelp

## 📝 Descripción del Proyecto
Este proyecto tiene como objetivo **analizar información de restaurantes obtenida mediante la API de Yelp**.  
Se realiza un proceso completo de **Exploración, Limpieza, Análisis y Visualización**, con el fin de identificar patrones en la oferta gastronómica y el comportamiento de los consumidores.  

El proyecto se desarrolla en tres fases:
1. **Exploratory Data Analysis (EDA):** inspección inicial, limpieza y detección de outliers.  
2. **Extracción de Datos (API Yelp):** conexión y descarga de datos actualizados desde la API de Yelp.  
3. **Análisis Final:** integración de resultados, métricas descriptivas y visualizaciones para obtener conclusiones.  

---

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.10+  
- **Librerías:**  
  - `pandas`, `numpy` → Análisis y manipulación de datos  
  - `matplotlib`, `seaborn`, `plotly` → Visualización de datos  
  - `requests` → Conexión con la API de Yelp  
  - `dotenv` → Manejo seguro de credenciales  
- **Entorno:** Jupyter Notebook  

---

## 📂 Estructura del Repositorio
```
.
├── Avance_1_EDA.ipynb             # Análisis exploratorio de datos iniciales
├── Avance_2_API_Yelp.ipynb        # Extracción de información mediante la API de Yelp
├── Avance_Analisis_Final.ipynb    # Integración y conclusiones del análisis
├── requirements.txt               # Librerías necesarias para ejecutar el proyecto
└── README.md                      # Documentación del proyecto
```

---

## ⚙️ Instalación y Ejecución
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/usuario/repositorio.git
   cd repositorio
   ```
2. Crear un entorno virtual e instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Crear un archivo `.env` en la raíz del proyecto con tu API Key de Yelp:
   ```
   API_KEY=tu_api_key_aqui
   ```
4. Ejecutar los notebooks en Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📈 Principales Resultados
- Identificación de **categorías más populares** de restaurantes.  
- Análisis de la **frecuencia de visitas** y el **promedio de gasto de los clientes**.  
- Visualizaciones que muestran **tendencias por ubicación, género y estrato socioeconómico**.  
- Obtención de **insights clave** sobre la dinámica de la oferta gastronómica en la ciudad.  

---

## 🚀 Próximos Pasos
- Ampliar el dataset con más consultas a la API de Yelp.  
- Aplicar modelos de **Machine Learning** para segmentación de clientes.  
- Desplegar un dashboard interactivo con **Streamlit o Dash**.  

---

## 👨‍💻 Autor
Proyecto desarrollado por **[Tu Nombre]** como práctica de análisis de datos y uso de APIs en Python.  
