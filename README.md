# Análisis de Datos de Viajes en Nueva York en Taxis Verdes

Este repositorio contiene un análisis de datos de viajes en la ciudad de Nueva York utilizando el conjunto de datos de viajes en taxi proporcionado por [NYC Taxi & Limousine Commission](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). El análisis se realizó utilizando varias bibliotecas de Python, incluyendo pandas, numpy, matplotlib y seaborn.

## Descripción del Conjunto de Datos

El conjunto de datos contiene información sobre viajes en taxi verde, incluyendo detalles sobre la fecha y hora del viaje, la duración, la distancia, el costo total y la propina. 

También se cuenta con otro conjunto de datos con la ubicación, el punto de recogida y destino.

## Librerías Utilizadas

- [pyarrow](https://arrow.apache.org/docs/python/index.html)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

## Análisis Realizado

A lo largo del análisis, se exploraron diversas características del conjunto de datos para obtener información interesante sobre los viajes en Nueva York en taxis verdes. Algunos de los análisis realizados incluyen:

- Identificación de viajes con origen o destino en aeropuertos de Nueva York.
- Análisis de propinas por debajo del 5% en función de diferentes variables.
- Relación entre la distancia del viaje y el costo o la propina.
- Patrones temporales en los viajes, como horas del día y días de la semana más frecuentes.
- Comparación de propinas bajas con las propinas en general en diferentes momentos.

## Cómo Ejecutar el Código

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias necesarias utilizando `pip install -r requirements.txt`.
3. Ejecuta los scripts de análisis proporcionados, como `script_challenge.ipynb`.


