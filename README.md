# telecomX_LATAM1

# Descripción del proyecto

Este proyecto surge a partir de un desafío de Data Science en el que asumimos el papel de analista de datos dentro de Telecom X, una empresa de telecomunicaciones que está enfrentando un problema importante de cancelación de clientes (churn).

La meta principal es analizar la información histórica de los usuarios para entender qué factores están influyendo en la decisión de cancelar el servicio y, a partir de ello, dejar preparada la base para futuros modelos predictivos que permitan anticipar estas bajas.

El desarrollo del trabajo se realizó en Google Colab, utilizando principalmente Python, Pandas y Matplotlib para el procesamiento, análisis y visualización de los datos.

# Objetivos

El proyecto se planteó con cuatro objetivos claros:

Comprender el problema de negocio
Se buscó medir con precisión la tasa de churn e identificar cuáles son las características más comunes entre los clientes que cancelan el servicio.

Construir un proceso de ETL (Extracción, Transformación y Carga)
Esto incluyó extraer los datos desde una fuente externa (simulando una API desde GitHub), limpiarlos, transformarlos y organizarlos para obtener un DataFrame estructurado y listo para análisis.

Realizar un Análisis Exploratorio de Datos (EDA)
Se analizaron tanto variables numéricas como categóricas para detectar patrones, relaciones y tendencias asociadas al churn.

Generar conclusiones y recomendaciones de negocio
Con base en los hallazgos, se propusieron acciones concretas orientadas a reducir la evasión y fortalecer la fidelización de clientes.

# Datos

La información utilizada proviene del repositorio oficial del desafío en GitHub:

https://github.com/alura-cursos/challenge2-data-science-LATAM

El archivo principal es TelecomX_Data.json, que tiene una estructura JSON anidada. Además, se cuenta con un diccionario de datos (TelecomX_diccionario.md) que describe cada variable.

El JSON incluye:

Identificación del cliente (customerID) y estado de churn.

Bloques anidados relacionados con datos del cliente, servicios de telefonía, servicios de internet y detalles de la cuenta (incluyendo cargos).

# Tecnologías utilizadas

Lenguaje: Python

Entorno: Google Colab

Librerías principales:

pandas para manipulación y análisis de datos.

numpy para operaciones numéricas.

matplotlib para visualizaciones.

requests para obtener los datos desde la web.

# Principales hallazgos

La tasa de churn se ubica alrededor del 26–27 %, lo que confirma que es un problema significativo para la empresa.

Los clientes que cancelan suelen:

Tener menor antigüedad en la compañía.

Pagar cargos mensuales más altos.

Acumular menores cargos totales.

Los contratos mes a mes (Month-to-month) concentran la mayor tasa de cancelación, mientras que los contratos de uno o dos años muestran mucha mayor estabilidad.

El método de pago Electronic check presenta la tasa de churn más alta.

Los usuarios de fibra óptica tienen mayor probabilidad de cancelar en comparación con otros tipos de servicio.

La falta de servicios adicionales como OnlineSecurity o TechSupport está asociada a mayor riesgo de abandono.

