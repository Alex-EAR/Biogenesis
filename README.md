#**Análisis de Datos "Expansión estratégica de laboratorios para investigación y vacunación de COVID-19"**

**Descripción del Proyecto 📊**
Este proyecto tiene como objetivo analizar un conjunto de datos sintético relacionado con la incidencia del COVID-19, utilizando herramientas de análisis de datos y visualización. Se trabajó con un archivo CSV masivo, aplicando técnicas de procesamiento, análisis estadístico y visualización para extraer insights valiosos sobre la propagación de la enfermedad, la cobertura de vacunación y otros factores relevantes.

**Estructura del Proyecto 📂**
Preparación y Filtrado de Datos
Análisis Estadístico y Visualización
Análisis Exploratorio Avanzado (EDA)
Creación de Dashboard en Power BI

## **1. Preparación y Filtrado de Datos 🛠️**
Archivo Utilizado:

Dataset: CSV con 12,216,057 filas y 50 columnas.
Diccionario de Datos: Archivo README complementario para comprender las columnas.
Pasos Realizados:

Carga de Datos: Se utilizó un archivo Jupyter Notebook para cargar el CSV.
Filtrado:
Selección de datos por países específicos.
Filtrado de fechas posteriores a enero de 2021.
Limpieza:
Eliminación de registros nulos.
Ajuste de tipos de datos según la naturaleza de cada columna.
Identificación de Variables Clave:
Se seleccionaron variables relevantes para el análisis.
Estadísticas Descriptivas:
Mediana, varianza, rango, entre otros.
Resultados:
Estas medidas ofrecen insights sobre la dispersión de los datos, proporcionando una base sólida para análisis posteriores y facilitando la toma de decisiones informadas.

## **2. Análisis Estadístico y Visualización 📈**
Bibliotecas Utilizadas:

Pandas y NumPy para cálculos estadísticos.
Matplotlib y Seaborn para visualizaciones.
Análisis Realizados:

Medidas Estadísticas:
Tendencia central (media, mediana, moda).
Medidas de dispersión (varianza, desviación estándar).
Correlaciones entre variables.
Visualizaciones Generadas:
Histogramas.
Gráficos de barras.
Mapas de calor.
Diagramas de dispersión.
Aspectos Analizados:

Distribución de la incidencia de COVID-19.
Tasas de vacunación.
Exploración de relaciones entre variables (por ejemplo, incidencia vs. temperatura).
Resultados:
Se identificaron patrones y tendencias a largo plazo, considerando factores geográficos y climáticos. Las visualizaciones personalizadas mejoraron la comprensión de la distribución y permitieron detectar áreas prioritarias para asignar recursos.

## **3. Análisis Exploratorio Avanzado (EDA) 🔍**
Enfoque:
Se aplicaron técnicas avanzadas para un análisis más profundo del dataset.

Pasos Clave:

Series Temporales:
Análisis de la evolución de casos activos, recuperados, y tasas de crecimiento.
Correlaciones Avanzadas:
Evaluación de posibles relaciones entre variables como urbanización, cobertura de vacunación y condiciones preexistentes.
Funciones Personalizadas:
Aplicación de operaciones específicas sobre cada columna para extraer patrones ocultos.
Objetivos:
Evaluar la efectividad de diferentes estrategias de vacunación y comprender cómo factores externos impactan en la propagación del COVID-19.

## **4. Dashboard en Power BI 📊**
Integración de Resultados:

Se importó el conjunto de datos previamente analizado a Power BI.
Se diseñó un dashboard interactivo para visualizar:
Incidencia de COVID-19.
Cobertura de vacunación.
Correlaciones entre variables clave.
Características del Dashboard:

Visualizaciones dinámicas y personalizadas.
Exploración interactiva para los usuarios.
Facilita la toma de decisiones estratégicas mediante una presentación clara de los resultados.
Herramientas Utilizadas 🛠️
Python: Pandas, NumPy, Matplotlib, Seaborn.
Power BI: Creación de dashboards interactivos.
Jupyter Notebook: Desarrollo y documentación del análisis.

## **Conclusión 🎯**
Este proyecto proporciona un análisis integral de los datos relacionados con el COVID-19, combinando estadísticas descriptivas, visualización y análisis exploratorio avanzado. La integración en Power BI permite a los usuarios explorar los resultados de manera interactiva, facilitando la toma de decisiones informadas sobre estrategias de control y asignación de recursos.
