Proyecto Análisis de Evasión de Clientes (Churn)
📌 Descripción del Proyecto

Este proyecto analiza la evasión de clientes (churn) en la empresa Telecom X, buscando entender los factores que influyen en la pérdida de clientes.
El análisis permite identificar patrones, generar insights de negocio y sentar las bases para futuros modelos predictivos que ayuden a reducir la tasa de cancelación.
🎯 Objetivos

    Importar y procesar datos provenientes de un archivo JSON con información de clientes.

    Aplicar un flujo ETL (Extracción, Transformación y Carga) para limpiar y estructurar los datos.

    Realizar un Análisis Exploratorio de Datos (EDA) para identificar patrones y variables relevantes.

    Generar gráficos descriptivos de la evasión de clientes.

    Proponer recomendaciones estratégicas basadas en los resultados.

    Estructura del Proyecto

├── data/
│   ├── TelecomX_Data.json       # Dataset original
│
├── notebooks/
│   ├── 01_ETL_Limpieza.ipynb    # Extracción, transformación y carga
│   ├── 02_EDA_Analisis.ipynb    # Análisis exploratorio con gráficos
│   ├── 03_Informe_Final.ipynb   # Insights y conclusiones
│
├── README.md

Cómo ejecutar el proyecto

    Abrir el notebook en Jupyter o Google Colab.

    Ejecutar las celdas paso a paso:

        ETL: Importación y limpieza de datos.

        EDA: Visualizaciones y análisis descriptivo.

        Informe: Resumen de conclusiones y recomendaciones.

    Asegurarse de tener el archivo TelecomX_Data.json dentro de la carpeta data/.

Pasos de Limpieza y Tratamiento

    Normalización de columnas anidadas (customer, phone, internet, account).

    Conversión de datos a tipos correctos (float, int).

    Creación de nueva variable Cuentas_Diarias.

    Estandarización de columnas categóricas (Sí/No → 1/0) y traducción de valores al español.

    Manejo de valores faltantes en Evasión.

Análisis Exploratorio (EDA)

    Distribución general de la evasión (clientes retenidos vs cancelados).

    Churn por variables categóricas (tipo de contrato, método de pago, servicios contratados).

    Churn por variables numéricas (meses de contrato, cargos mensuales, cargos totales).

    Gráficos de barras, circulares y boxplots para visualización de patrones.

Resultados Principales

    Evasión más alta en clientes con contratos mensuales y método de pago mediante cheque electrónico.

    Clientes con baja antigüedad tienen mayor tasa de cancelación.

    Planes más caros y sin servicios extra tienden a cancelar más rápido.

    La fidelización inicial y beneficios en planes anuales son clave para reducir el evacion (perdida de clientes). 
    
    
    

