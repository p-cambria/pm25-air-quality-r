# Análisis y visualización de datos de PM2.5 con R

Exploración de distribuciones, diferencias geográficas y valores atípicos en registros de calidad del aire de la EPA.

## Problema y objetivo

Describir cómo se distribuyen las concentraciones promedio registradas de PM2.5 y explorar diferencias entre estados y regiones mediante visualizaciones estadísticas y geográficas.

Proyecto académico del curso Fundamentos de Ciencia de Datos.

## Datos

- Fuente institucional: Agencia de Protección Ambiental de Estados Unidos (EPA).
- Archivo identificado en el proyecto: `annual_conc_by_monitor_2022.csv`.
- Selección: observaciones de `PM2.5 - Local Conditions`.
- Variable principal: `Arithmetic Mean`.

## Metodología

1. Selección y preparación de los registros correspondientes al contaminante de interés.
2. Histogramas y curvas de densidad para explorar la distribución.
3. Boxplots por estado y región para comparar grupos y detectar observaciones extremas.
4. Mapas georreferenciados y comparaciones entre variables categóricas.
5. Exploración de posibles distribuciones mediante una muestra aleatoria de 5,000 observaciones y el uso complementario de EasyFit.

La muestra de 5,000 observaciones corresponde a una etapa del análisis; no se presenta como el tamaño total de la base original.

## Hallazgos descritos en el trabajo

El análisis identificó diferencias entre estados y regiones, presencia de valores atípicos y señales de asimetría positiva en la variable principal. La evidencia gráfica y los resultados de ajuste se incorporarán desde los archivos originales.

## Herramientas

R · RStudio · R Markdown · ggplot2 · EasyFit.

## Autor

Pablo Cambria · [LinkedIn](https://www.linkedin.com/in/pablo-cambria-6375b3217)
