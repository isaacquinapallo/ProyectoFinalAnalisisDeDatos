### 1.- Extracción de Datos

La primera fase del proyecto se enfoca en la extracción de datos relacionados con el COVID-19 desde dos fuentes principales: Kaggle y Statista. Los datos extraídos son cruciales para analizar el impacto de la pandemia en diferentes aspectos, incluyendo casos, muertes y vacunaciones. Los conjuntos de datos específicos a extraer son:

- FechasPersonasCuradas: Registro de fechas y cantidades de personas que se han recuperado del COVID-19 en diferentes países. -PaisesPersonasPolaridad: Información sobre la polarización de opiniones en diversos países con respecto a las medidas y consecuencias del COVID-19. -PaisesPersonasEnfermas: Estadísticas sobre el número de personas contagiadas con COVID-19 en varios países. -PaisesPersonasMuertesEnfermedad: Datos sobre la mortalidad por COVID-19 en distintos países. -PaisesPersonasVacunadas: Información sobre las tasas de vacunación contra el COVID-19 en todo el mundo.

En particular, Statista proporcionará los datos sobre: -PaisesPersonasMuertesEnfermedad: Detalles sobre la mortalidad por COVID-19, desglosados por país. -PaisesPersonasVacunadas: Datos sobre la cantidad de personas vacunadas contra el COVID-19 en cada país.

Estos datos serán fundamentales para comprender la evolución de la pandemia y la eficacia de las medidas adoptadas.

### 2.- Scripts

Para manejar adecuadamente los datos extraídos, se desarrollarán scripts que permitan su correcta transformación y formateo. Estos scripts cumplirán con las siguientes tareas:

- Transformación y Formato: Los datos obtenidos estarán en varios formatos como JSON, CSV y XLS. Los scripts se encargarán de transformar estos formatos para que todos los datasets estén en formato CSV, que es más adecuado para su análisis en herramientas como Power BI.

- Ejemplos de procesos específicos: -PaisesPersonasMuertesEnfermedad.json -> Conversión a CSV, facilitando el análisis comparativo entre países. -PaisesPersonasVacunadas.xls -> Limpieza y conversión a CSV para asegurar la uniformidad del dataset. -FechasPersonasCuradas.json -> Transformación en un formato accesible para su integración en bases de datos y análisis posterior. -Corrección de Datos: Los scripts también corregirán cualquier inconsistencia en los datos para asegurar que la información esté lista para su uso en las visualizaciones y análisis.

### 3.- Visualizaciones

En la última fase del proyecto, se utilizará Power BI para crear visualizaciones que representen claramente la evolución y el impacto del COVID-19. Esta fase incluye:

- Integración de Datos: Los datos transformados y corregidos serán integrados en Power BI para su análisis. Se utilizarán los cinco datasets previamente procesados para asegurar una visualización coherente y completa.

- Creación de Gráficos: Se desarrollarán gráficos que mostrarán:

- La evolución temporal de los casos de personas curadas y vacunadas. -Mapas interactivos que demuestren la propagación y el impacto del COVID-19 en diferentes regiones. -Gráficos comparativos que permitan analizar las tasas de infección y mortalidad entre los países.

- Análisis e Interpretación: Las visualizaciones permitirán identificar patrones, tendencias y correlaciones clave en los datos, lo que facilitará la extracción de insights sobre la evolución de la pandemia y la efectividad de las respuestas globales.
