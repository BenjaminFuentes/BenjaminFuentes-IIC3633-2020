# Crítica BPR: Bayesian Personalized Ranking from Implicit Feedback

En este paper, al igual que en la lectura anterior, se plantea un método para trabajar sistemas recomendadores que tienen como input un feedback implicito. Para esto desarrollan un modelo de optimización basado en un analisis bayeseano para lograr generar un ranking personalizado para usuarios. Para este criterio de optimizacion usan una distribución a posteriori con la cual desarrollan un algoritmo de aprendizaje. Con este algoritmo implementan otros metodos utilizados en la literatura que son un knn adaptivo y una factorización matricial.

Gran parte de esta investigación se basa en el analisis matemático que permite llegar a su algoritmo, que si bien es bastante interesante, contiene una notación específica que es bastante complicada de seguir. Si bien llegan a resultado satisfactorios y que sobrepasan a las otras opciones en esta área teóricamente, la experimentación fue acotada y no deja en claro esta diferencia en el rendimiento.

Creo que el paper plantea una solución muy creativa en el área que puede ser muy interesante seguir trabajando y sobre todo realizar distintos experimentos prácticos que permitan una comparación exhaustiva con los otros métodos de ranking personalizado en feedback implicito.
