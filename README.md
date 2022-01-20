<!-- 
You can use the [editor on GitHub](https://github.com/edwardptera/Gravimetro/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
-->

# Gravimetro

En esta pagina web se encuentran publicados algunos recursos interactivos con temas de gravimetría aprovechando las maquinas virtuales de Google Colaboratory, que pueden ejecutarse en cualquier ordenador desde el navegador temporalmente.

## Gravity

Conjunto de notebooks interactivos que simulan las características básicas de un gravímetro tipo LaCoste & Romberg, explicaciones básicas sobre correcciones gravimetricas.

* **Gravedad Teorica:** Cálculos de la gravedad teórica modelando la Tierra como un elipsoide con valores de los parámetros a lo largo del tiempo y sus diferencias.
* **Correcciones:** Correcciones aire libre, bouger...
* **Deriva Instrumental:**  Ejemplo de calculo de deriva intrumental.
* **Unicidad:**  Problema de unicidad en inversión gravimetrica.
* **Trypod:**  Ajuste del tripode.

|Notebook|<img height=32 src="https://colab.research.google.com/img/favicon.ico"/>|
|:-:|:-:|
|Gravedad Teorica|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Gravedad_Teorica.ipynb)|
|Correcciones|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Correcciones.ipynb)|
|Deriva Instrumental|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Deriva_Instrumental.ipynb)|
|Unicidad|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Unicidad.ipynb)|
|Trypod|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Trypod.ipynb)|

## RJMCMC

Conjunto de notebooks interactivos que muestran el método de inversión gravimétrica con el algoritmo Reverse-Jump Markov Chain Montecarlo (RJMCMC).

* **Grupo 1**, los estudiantes podrán interactuar con el método directo (usando la ecuación de Talwani) en un modelo simplificado en 2D.

<!-- Ahora con Gradio. 
<img height=32 src="https://gradio.s3-us-west-2.amazonaws.com/2.4.0/static/media/logo.411acfd1.svg"/>
<img height=32 src="https://i.ibb.co/6DVLqmf/noun-tools-2220412.png"/> -->

* **Grupo 2**, los estudiantes usaran el algoritmo RJMCMC para realizar una inversión gravimétrica utilizando, por ejemplo, los datos de anomalías gravimétricas por el grupo 1.


|Notebook|<img height=32 src="https://colab.research.google.com/img/favicon.ico"/>|
|:-:|:-:|
|Grupo1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/RJMCMC/RJMCMC_Grupo1.ipynb)|
|Grupo2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/RJMCMC/RJMCMC_Grupo2.ipynb)|

## ML

Conjunto de notebooks con métodos de regresión con Macgine Learning (ML) para completar anomalías gravimétricas según la base de datos de [gravimetria del NOAA](https://www.ngdc.noaa.gov/mgg/gravity/) GRAVCD-colomb97 realizada por Instituto Geográfico Agustín Codazzi (IGAC) en 1997

* **Shapefiles:** Se crea un archivo `shapefile` del croquis de Colombia uniendo información de [naturalearthdata](https://www.naturalearthdata.com/) y la [DIAN](https://geoportal.dane.gov.co/). Y se crea el archivo `shapefile` del rectángulo con de área de estudio.
* **NOAA-Gravity:**  Se descarga y organiza la base de datos [GRAVCD-colomb97](https://www.ngdc.noaa.gov/mgg/gravity/1999/data/regional/colomb97/)
* **SRTM:** Se utiliza la librería [srtm.py](https://github.com/tkrajina/srtm.py) para descargar información de elevaciones [Shuttle Land Elevation Data]( https://www2.jpl.nasa.gov/srtm/)
* **IA:** Se definen y entrenan los métodos de Machine Learning con los cueles se harán las regresiones para Colombia, Antioquia y el área de Estudio
* **Maps:** Se crean los mapas con las predicciones y comparaciones de los resultados.


|Notebook|<img height=32 src="https://colab.research.google.com/img/favicon.ico"/>|
|:-:|:-:|
|Shapefiles|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/Shapefiles.ipynb)|
|NOAA-Gravity|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/NOAA-Gravity.ipynb)|
|SRTM|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/SRTM.ipynb)|
|IA|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/IA.ipynb)|
|Maps|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/Maps.ipynb)|