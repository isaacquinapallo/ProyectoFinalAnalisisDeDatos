Explicación de la Arquitectura para el Proyecto "Noticias y Eventos Mundiales"
La arquitectura mostrada en la imagen corresponde a una sección del proyecto de análisis de datos enfocado en Noticias y Eventos Mundiales. A continuación, se detalla el flujo de datos y la interacción entre las diferentes fuentes y herramientas utilizadas:

1.Recopilación de Datos:

-Fuentes Web: Se recopilan datos de diversas fuentes web, representadas por los iconos de globos terráqueos en la parte izquierda. Estas fuentes incluyen información sobre países, personas, enfermedades, muertes, y vacunaciones relacionadas con eventos globales y pandemias.

-Los datos son recolectados en formatos diversos como CSV y JSON.

2.Procesamiento de Datos:

-CouchDB: Parte de los datos recogidos en formato JSON se almacenan en CouchDB, una base de datos NoSQL orientada a documentos. Esta etapa es crucial para manejar datos semiestructurados provenientes de fuentes web.

-MongoDB: Posteriormente, algunos de estos datos se transfieren a MongoDB, otra base de datos NoSQL, para un manejo más eficiente y escalable de grandes volúmenes de información.

-Transformación de Formatos: Durante el proceso, los datos pasan por varias transformaciones de formato, incluyendo conversiones de JSON a CSV y viceversa, así como de XLS a CSV. Esto permite estandarizar los datos para un análisis más efectivo.

3.Integración y Almacenamiento Final:

-Los datos procesados y transformados en MongoDB se preparan para ser exportados en formato CSV.

4.Visualización en Power BI:

-Finalmente, los datos ya estructurados y limpios en formato CSV se integran en Power BI, la herramienta de visualización utilizada en el proyecto. Aquí, se generan dashboards interactivos que permiten visualizar, analizar y extraer insights significativos de los datos relacionados con Noticias y Eventos Mundiales.

Este flujo de trabajo demuestra la capacidad de manejar, transformar e integrar múltiples fuentes de datos utilizando bases de datos NoSQL (CouchDB y MongoDB), para finalmente utilizarlas en la visualización y análisis en Power BI. Esto no solo permite un análisis profundo de los eventos y noticias globales, sino que también facilita la toma de decisiones basada en datos.

