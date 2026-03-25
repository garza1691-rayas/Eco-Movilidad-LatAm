# 📈 Análisis de Correlación: Movilidad Urbana vs. Productividad Económica (LatAm)

## 🎯 Objetivo del Proyecto
Este proyecto busca evaluar la relación entre la congestión vehicular y el rendimiento económico en las principales metrópolis de Latinoamérica. Utilizando datos de tráfico en tiempo real y métricas de productividad urbana, el análisis identifica en qué ciudades la falta de infraestructura de transporte actúa como un cuello de botella para el crecimiento del PIB.

---

## 🛠️ Herramientas y Tecnologías
- **Python 3.x**: Lenguaje principal para el procesamiento de datos.
- **Pandas & NumPy**: Limpieza, manipulación y tratamiento de valores nulos (Imputación estadística).
- **SQL**: Extracción y segmentación de datos relacionales.
- **Matplotlib & Seaborn**: Visualización de correlaciones y distribuciones.
- **Fuentes de Datos**: 
  - [TomTom Traffic Index](https://www.tomtom.com/traffic-index/) (Datos de congestión).
  - [OECD Cities Database](https://stats.oecd.org/) (PIB y Productividad).

---

## 📋 Metodología (Data Pipeline)

### 1. Extracción y Limpieza (ETL)
Se integraron datasets de fuentes heterogéneas mediante operaciones de `Merge` y `Join`. Se realizó un análisis de calidad de datos detectando un [X]% de valores faltantes en métricas de emisiones de $CO_2$.

### 2. Tratamiento de Datos
- **Imputación**: Se aplicó una estrategia de **imputación por mediana global** para mantener la consistencia estadística.
- **Normalización**: Ajuste de escalas entre el índice de tráfico y el PIB per cápita.

### 3. Análisis Crítico y Mejoras
- **Fortaleza**: El modelo permite identificar ciudades con alta productividad pero eficiencia de movilidad crítica.
- **Propuesta de Mejora**: Implementación de **K-Means Clustering** para agrupar ciudades por nivel de desarrollo, evitando sesgos en la comparación entre megaciudades y ciudades intermedias.

---

## 📊 Hallazgos Clave (Insights)
- Existe una correlación de [0.XX] entre las horas perdidas en tráfico y la pérdida de productividad en ciudades como CDMX y São Paulo.
- Las ciudades con mayor inversión en infraestructura de transporte masivo muestran una resiliencia económica superior frente a picos de congestión.

---

## 🚀 Visualización del Proyecto
Puedes ver el reporte interactivo y el análisis detallado aquí:
👉 **[Ver Análisis en GitHub Pages](TU_URL_DE_GITHUB_PAGES)**

---

## 🧑‍💻 Autor
**[Tu Nombre]** - Analista de Datos Jr.
*Especialista en Diagnóstico Técnico con enfoque en precisión de datos.*

- [LinkedIn](TU_URL_LINKEDIN)
- [GitHub](TU_URL_GITHUB)
