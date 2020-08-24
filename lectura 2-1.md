﻿# Crítica Collaborative Filtering for Implicit Feedback Datasets

En este paper se trabaja un foco importante dentro de los sistemas recomendadores que es el Collaborative filtering, basandose principalmente en la información implicita que puede entregar un usuario. Esto es muy util, dado que en variada ocaciones no es posible tener gustos o raitngs explicitos de los usuarios.  Para lograr esto, plantean un modelo de optimización que permite llegar a una expresión que toma un input que es la observación y lo convierte en dos variable que son la preferencia y la confianza que existe en ese valor. Hay que notar que el input u observación tiene ciertas dificultades como por ejemplo que no logra entregar un feedback negativo, puede contener mucho ruido y su valor no significa una mayor preferencia como lo es en información explicita.

Recalco mucho el trabajo matricial y matemático que contiene esta investigación, ya que permite llegar a expresiones coherentes y con cierta interpretabilidad a partir de un input bastante vago y díficil de trabajar. Sin embargo, no queda muy claro el resultado obtenido en cuanto a la explicación de las recomendaciones lo cual tiene relevancia en el tema y tendrá que seguir trabajandose a futuro.

Mi mayor crítica a este paper es la parte de experimentación. Si bien existe una base de datos muy buena, creo que la manera de evaluar rendimiento no es tan clara y no se realizan las mejores comparaciones. Me hubiera gustado analizar como varia el rendimiento de un sistema con input implicito cuando se cambia el significado de la variable *r_ui* o agregar otras observaciones implicitas que no sean solo la cantidad de veces o minutos que se observo el programa. 

Creo que el paper llega a buenas conclusiones y permite un analisis satisfactorio en cuanto al area de feedback implicito y tiene buen potencial para seguir trabajando el modelo planteado en este.