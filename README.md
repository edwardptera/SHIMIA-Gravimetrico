<!-- 
You can use the [editor on GitHub](https://github.com/edwardptera/Gravimetro/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
-->

# Gravimetro

En esta pagina web se encuentran publicados algunos recursos interactivos con temas de gravimetría aprovechando las maquinas virtuales de Google Colaboratory, que pueden ejecutarse en cualquier ordenador desde el navegador temporalmente.

## Gravity

Conjunto de notebooks interactivos que simulan las características básicas de un gravímetro tipo LaCoste & Romberg, explicaciones básicas sobre correcciones gravimetricas.

* **Gravedad Teorica:** Cálculos de la gravedad teórica modelando la Tierra como un elipsoide con valores de los parámetros a lo largo del tiempo y sus diferencias.
* **Correcciones:** Correcciones aire libre, bouger
* **Deriva Instrumental:**  Ejemplo de calculo de deriva intrumental

|Notebook|<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />|
|:-:|:-:|
|Gravedad Teorica|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Gravedad_Teorica.ipynb)|
|Correcciones|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Correcciones.ipynb)|
|Deriva Instrumental|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/Gravimetry/Deriva_Instrumental.ipynb)|

## ML

Conjunto de notebooks con métodos de regresión con Macgine Learning (ML) para completar anomalías gravimétricas según la base de datos de [gravimetria del NOAA](https://www.ngdc.noaa.gov/mgg/gravity/) GRAVCD-colomb97 realizada por Instituto Geográfico Agustín Codazzi (IGAC) en 1997

* **Colombia union:** Se crea un archivo `shapefile` del croquis de Colombia uniendo información de [naturalearthdata](https://www.naturalearthdata.com/) y la [DIAN](https://geoportal.dane.gov.co/).
* **my rectangle:** Se crea el archivo `shapefile` del rectángulo con de área de estudio.
* **SRTM:** Se utiliza la librería [srtm.py](https://github.com/tkrajina/srtm.py) para descargar información de elevaciones [Shuttle Land Elevation Data]( https://www2.jpl.nasa.gov/srtm/)
* **Data:**  Se descarga y organiza la base de datos [GRAVCD-colomb97](https://www.ngdc.noaa.gov/mgg/gravity/1999/data/regional/colomb97/)
* **IA:** Se definen y entrenan los métodos de Machine Learning con los cueles se harán las regresiones para Colombia, Antioquia y el área de Estudio
* **Maps:** Se crean los mapas con las predicciones y comparaciones de los resultados.


|Notebook|<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />|
|:-:|:-:|
|Colombia union|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/Colombia_union.ipynb)|
|my rectangle|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/my_rectangle.ipynb)|
|SRTM|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/SRTM.ipynb)|
|Data|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/Data.ipynb)|
|IA|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/IA.ipynb)|
|Maps|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/ML/Maps.ipynb)|

## RJMCMC

Conjunto de notebooks interactivos que muestran el método de inversión gravimétrica con el algoritmo Reverse-Jump Markov Chain Montecarlo (RJMCMC).

* **Grupo 1**, los estudiantes podrán interactuar con el método directo (usando la ecuación de Talwani) en un modelo simplificado en 2D.

<!-- Ahora con Gradio. ![Gradio](https://gradio.app/static/home/img/logo_inline.svg) -->

* **Grupo 2**, los estudiantes usaran el algoritmo RJMCMC para realizar una inversión gravimétrica utilizando, por ejemplo, los datos de anomalías gravimétricas por el grupo 1.


|Notebook|<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />|
|:-:|:-:|
|Grupo1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/RJMCMC/RJMCMC_Grupo1.ipynb)|
|Grupo2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardptera/Gravimetro/blob/main/RJMCMC/RJMCMC_Grupo2.ipynb)|