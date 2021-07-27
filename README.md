# COM4001_Proyecto_Final
Proyecto Final para el curso de minería de datos, 2021 primer semestre de la Universidad de O'Higgins.

Integrantes:
  Camila Muñoz, Ingeniería Civil Geológica '\n'
  Yerko Sepúlveda, Ingeniería Civil en Computación
  
Para replicar el trabajo se recomienda usar un ambiente virtual environment.yml para no tener problemas con las versiones de las bibliotecas utilizadas.
Se incluye los datos utilizados, extraidos desde https://earthquake.usgs.gov/earthquakes/search/, agregando una columna 'tipo de sismicidad', 
la cual hace referencia si es intraplaca o interplaca, con la condicion de =SI(D2<60,1,0), donde D2 hace referencia a la profundidad.

