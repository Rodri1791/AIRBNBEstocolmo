# AIRBNB Estocolmo <img src="https://www.dscasturias.com/WebRoot/StoreES3/Shops/ec8259/5B22/3B17/5576/7419/600F/52DF/D016/E45D/images.jpg" style="width: 5%; height: auto;" />
<br>
<center><img src="http://t1.gstatic.com/licensed-image?q=tbn:ANd9GcTuLVGfMg8-jJj04stBtD2EdQCeQgJdNpCZGVw2QnHCjAJq-KZe9jl0EXwU5DZTzreH"></center>
<br>


Limpieza, transformación y análisis exploratorio de un dataset con datos de airbnbn de Estocolmo.
En este caso solo subí el notebook con el código y los gráficos dividido de esta forma:
- Limpieza y descripción de datos
- Análisis exploratorio:
  + Distribución y cantidad de hospedajes de los barrios de Estocolmo.
  + Análisis de los diferentes tipos de hospedaje que ofrece airbnb en esta ciudad.
  + Análisis numero de alojados que ofrece
- Vemos un caso un poco anómalo
- Análisis de los precios y las reviews
  + Precio medio por barrio
  + Análisis de las reviews
  + Puntuaciones generales y por barrio
  + ¿Que es un superhost?
  + Disponibilidad de alojamientos en el tiempo
  + Precio medio por día
- Por ultimo hago una minería de texto en donde muestro las palabras más utilizadas en los comentarios de los alojamientos
  
Utilice como regla general plotly-express para los gráficos.


El conjunto de datos contiene un total de 6 archivos.

- listingsRW.csv = Datos detallados de listados
- calendar.csv = Datos detallados del calendario
- review.csv = Datos de las revisiónes detallados
- listing.csv = Resumen de información y métricas para listados en Estocolmo (bueno para visualizaciones).
- reviews.csv = Resumen de los datos de revisiones y un listado de ID (para facilitar el análisis basado en el tiempo y las visualizaciones vinculadas a un listado).
- neighbourhood.geojson = Archivo GeoJSON de barrios de la ciudad.

El identificador único en el conjunto de datos es la identificación de "listings". Esta es básicamente la identificación del anuncio.

<div id="header" align="center">
  <img src="https://media.giphy.com/media/MkxUqzY4yRQrXMjp7M/giphy.gif" width="300"/>
</div>


# AIRBNB Stockholm <img src="https://www.comprarbanderas.es/images/banderas/400/14-reino-unido_400px.jpg" style="width: 5%; height: auto;" />

<br>
<center><img src="http://t1.gstatic.com/licensed-image?q=tbn:ANd9GcTuLVGfMg8-jJj04stBtD2EdQCeQgJdNpCZGVw2QnHCjAJq-KZe9jl0EXwU5DZTzreH"></center>
<br>

Cleaning, transformation and exploratory analysis of a dataset with Stockholm airbnbn data.
In this case I only uploaded the notebook with the code and graphics divided in this way:
- Cleaning and description of data
- Exploratory analysis:
  + Distribution and quantity of lodgings in the neighborhoods of Stockholm.
  + Analysis of the different types of accommodation offered by airbnb in this city.
  + Analysis number of lodgers offered
- I show a slightly anomalous case
- Analysis of prices and reviews
  + Average price per neighborhood
  + Analysis of the reviews
  + Overall scores and by neighborhood
  + What is a superhost?
  + Availability of accommodation over time
  + Average price per day
- Finally I do a text mining where I show the most used words in the comments of the accommodations

I use plotly-express for charts.

The dataset contains 6 files.

- listingsRW.csv = Detailed listings data
- calendar.csv = Detailed calendar data
- review.csv = Detailed review data
- listing.csv = Summary information and metrics for listings in Stockholm (good for visualizations).
- reviews.csv = Summary of reviews data and a listing of IDs (to facilitate analysis based on time and views linked to a listing).
- neighborhood.geojson = GeoJSON file of city neighborhoods.

The unique identifier in the data set is the "listings" id. This is basically the ad id.

<div id="header" align="center">
  <img src="https://media.giphy.com/media/MkxUqzY4yRQrXMjp7M/giphy.gif" width="300"/>
</div>
