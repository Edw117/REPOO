US Vehicle Advertisement Listings Dashboard 

Para mí, el proyecto es una forma de demostrar que sé cómo funciona el ciclo de vida del 
desarrollo de software. 💻 Es como un "juego de mesa" donde el objetivo no es ganar analizando 
los datos, sino demostrar que puedo seguir todas las reglas del juego.

Paso 1: Configuro mi tablero (el entorno virtual) para que las piezas no se mezclen con otros juegos. 
Esto demuestra que soy una persona organizada y que mi trabajo no causará problemas a los demás.

Paso 2: Construyo la aplicación web (la parte interactiva del juego). En lugar de solo decirte los resultados, 
te doy las herramientas para que los veas tú mismo, como si estuvieras jugando. 
Esto muestra que sé cómo crear soluciones que la gente pueda usar.

Paso 3: Pongo el juego en un lugar público (la nube) para que cualquiera pueda jugar sin tener que ir a mi casa.
Esto me hace parecer un profesional capaz de compartir su trabajo y colaborar con otros.

En resumen, no es solo un análisis de datos. Es la prueba de que puedo llevar una idea desde el inicio hasta el final,como lo haría un verdadero ingeniero de software.



Este proyecto no es solo un análisis de datos, sino una demostración de que puedo llevar una idea desde el inicio hasta el final, siguiendo buenas prácticas del ciclo de vida del desarrollo de software.

El objetivo es crear un dashboard interactivo que permita explorar datos de anuncios de vehículos usados en Estados Unidos, respondiendo preguntas de interés de manera visual e intuitiva.

Contexto

Los anuncios de vehículos contienen información valiosa sobre precios, fabricantes, modelos, condiciones y características. Este dashboard facilita la exploración de esos datos para:

Identificar tendencias en los precios de vehículos.
-Comparar fabricantes y modelos más frecuentes.
-Analizar distribuciones por año, tipo de combustible, transmisión y condición.
-Proveer una herramienta visual e interactiva en lugar de un análisis estático.

⚙Funcionalidades del Dashboard

El dashboard incluye varias secciones interactivas construidas con Plotly y Streamlit:

Visualización de datos crudos
Muestra el dataset procesado para consulta directa.
Histogramas y gráficos de distribución
Tipos de vehículos por fabricante.
Distribución de precios.
Comparaciones entre variables relevantes (ej. condición, combustible, transmisión).

Interactividad
El usuario puede explorar los gráficos y obtener insights dinámicamente.

Despliegue en la nube
El dashboard se puede ejecutar localmente o publicarse en una plataforma como Streamlit Cloud o Heroku para acceso público.

Instalación y Uso
1. Clonar el repositorio
git clone https://github.com/usuario/vehicles-dashboard.git
cd vehicles-dashboard

2. Crear y activar un entorno virtual
python -m venv venv
source venv/bin/activate   # En Linux/Mac
venv\Scripts\activate      # En Windows

3. Instalar dependencias
pip install -r requirements.txt

4. Ejecutar el dashboard
streamlit run app.py

Estructura del repositorio
vehicles-dashboard/
│
├── app.py                 # Código principal del dashboard
├── vehicles_us_cleaned.csv # Dataset procesado
├── requirements.txt        # Dependencias del proyecto
├── README.md               # Documentación del proyecto
└── notebook.ipynb          # Análisis preliminar y limpieza de datos

Notebook

El archivo notebook.ipynb contiene:
El proceso de limpieza de datos.
Una breve exploración inicial de las variables.
Preparación del dataset final para ser usado en el dashboard.
Para mayor claridad, el notebook está formateado con:
Secciones bien definidas: Carga de datos, Limpieza, EDA básica.
Comentarios y explicaciones en cada celda.

Conclusión

Este proyecto no es únicamente un análisis de datos:
Demuestra la capacidad de organizar un entorno de trabajo limpio.
Construir una aplicación web interactiva que cualquiera puede usar.
Publicar y compartir el resultado como un profesional.

Enlace: https://nr2-yl93.onrender.com
