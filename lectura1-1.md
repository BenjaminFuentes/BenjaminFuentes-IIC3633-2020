Item-based Collaborative filtering Recommendation Algorithms
=============

El paper de esta semana hace un analisis de algoritmos de sistemas recomendadores y realiza una comparasión entro los sistemas basados en los usarios y los sistemas que se basan en los "items". Por un lado, el sistema basado en usuarios, se fija en las opiniones o ratings que emiten los usuarios respecto a un item y busca comparar usuarios con gustos similares en base a esto. Luego, dado un usuario activo y utilizando generalmente un algoritmo del tipo knn, se entrega una predicción de un item o una lista de items que a este usuario le puede interesar. Por el otro lado, un sistema basado en items, considera todos los items evaluados por un usuario y luego busca para un item determinado los más similares y a partir de esto se realiza una predicción. La dificultad de este metodo se basa en como encontrar similitudes entre distintos elementos y para esto se proponen 3 algoritmos.

Este paper hace un analisis detallado en cuanto a los dis tipos de sistema, lo que permite una lectura fluida. Además, explica de manera simple cada método, ejemplificandolos lo cual permite entender lo que se discute sin tener un conocimiento previo. Se discuten desafios actuales que tienen los sistemas recomendadores, como lo son en el caso de un sistema basado en usuarios la escalabilidad y la gran diferencia que hay entre cantidad de usuarios e items en una base de datos como la de amazon. Esto permite, que como lector, se logren identificar problemas y debelidades que tienen las recomendaciones y como se busca abordar esto.

En cuanto a la parte experimenta, se realiza un método cientifico apropiado y señala de manera detallada el procedimiento que se llevó acabo en el experimento. En lo personal, encuentro que se podría haber agregado más información respecto a la base de datos o algun tipo de visualización de los datos, para tener mayor entendimiento. Junto a esto, la presentación de los resultados no deja tan en claro la diferencia entre metodos. Quizas mostrar otros tipos de gráficos o la forma en que el sistema basado en items encuentra y predice la similitud entre items podría ayudar a entender los resultados obtenidos.

Finalmente, como una observación para continuar con la comparación entre estos métodos podría ser buena idea utilizar otra base de datos o en caso de usar la misma realizar el experimento utilizando distinta combinaciones aleatoreas de ratings de manera que la diferencia entre los rendimientos de ambos metodos no se vea afectada por los datos que se utilizan para entrenar y testear el algoritmo.




