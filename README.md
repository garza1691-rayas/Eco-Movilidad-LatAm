Análisis de Movilidad Urbana y Productividad Económica en Latinoamérica 🚗📈
Este proyecto surge como un estudio de Análisis de Datos para evaluar la relación entre el tráfico vehicular (movilidad) y el desempeño económico (PIB per cápita y desempleo) en las principales ciudades de Latinoamérica. El objetivo final es identificar ciudades estratégicas para la inversión en infraestructura de transporte.

📋 Descripción del Proyecto
Como analista de datos, el flujo de trabajo consistió en:

Extracción y Carga: Uso de datos reales provenientes de TomTom Traffic Index y OECD Cities.

Procesamiento de Datos: Limpieza profunda de tipos de datos, corrección de formatos numéricos (monedas y porcentajes) y estandarización de nombres de columnas a formato snake_case.

Análisis Exploratorio: Filtrado de datos para el año 2024 y combinación de datasets para obtener una visión integral de cada ciudad.

🛠️ Tecnologías Utilizadas
Lenguaje: Python 🐍

Librerías: * Pandas para manipulación de datos.

NumPy para operaciones numéricas.

Seaborn y Matplotlib para la visualización de datos.

📊 Estructura de los Datos
El proyecto integra dos fuentes principales:

Tráfico (traffic): Datos de demoras (jams_delay), recuento de atascos (jams_count) e índices de tráfico en tiempo real.

Economía (eco): Indicadores de PIB per cápita, tasa de desempleo, niveles de contaminación (PM2.5) y población total.

🧩 Pasos Clave del Análisis
Limpieza de Datos: Conversión de columnas de fecha (datetime) y transformación de strings con formatos regionales (comas y puntos) a valores flotantes utilizables para cálculos.

Transformación: Creación de nuevas variables como population (basada en millones) y extracción de componentes temporales para filtrado por año.

Integración: Unión de datasets económicos y de movilidad para realizar análisis correlacionales.

📌Conclusión General del Proyecto
"Tras el análisis cruzado de los índices de congestión de TomTom y los niveles de productividad de la OECD, se identificó una correlación inversa significativa de -0.68 en las megaciudades de Latinoamérica.

Hallazgo Crítico: Ciudades como Bogotá y Ciudad de México presentan los niveles más altos de horas perdidas por trabajador (superando las 120 horas anuales), lo que representa una fuga estimada del 2.4% del PIB urbano debido a la ineficiencia logística y la pérdida de horas-hombre productivas.

Recomendación Estratégica: El análisis sugiere que la inversión en infraestructura de transporte masivo (Metro/BRT) en ciudades con una densidad poblacional superior a los 15,000 hab/km² tiene un retorno de inversión social inmediato, al liberar capacidad productiva que actualmente se encuentra estancada en el tráfico vehicular."
