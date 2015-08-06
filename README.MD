# Instituciones padròn electoral CABA
## Descripción

Se encontrara en este proyecto un listado con todas las instituciones en las cuales se realizan los comicios en la ciudad autónoma de buenos aires.

El archivo cuenta con los siguientes datos:

* Nombre de la institución
* Dirección de la institución
* Número de comuna
* Latitud y Longitud de la institución
* Número total de mesas
* Mesas desde y mesas hasta

## Fuentes

Para obtener el archivo final se realizó la agrupación de múltiples fuentes:

1. Listado completo de Mesas del [Tribunal Superior de Justicia](https://www.eleccionesciudad.gob.ar)

  * https://www.eleccionesciudad.gob.ar/agrupaciones.php
  * https://www.eleccionesciudad.gob.ar/uploads/mesas-establecimientos-nacional.xlsx

2. Listado completo de las comunas porteñas de la pagina de [Buenos Aires Data](http://data.buenosaires.gob.ar)

  * http://data.buenosaires.gob.ar/dataset/comunas

3. API de [Mashape](https://www.mashape.com/shatsar/google-geocoding) para obtener la latitud y longitud de los establecimientos
