# Analyse critique sur le traitement des données

Selon moi: 

1- Pour faire une analyse aussi importante mettant en danger des vies humaines, il est nécessaire d'avoir un dataset bien plus grand portant beaucoup plus d'informations. Contrairement à ce qui a été utilisé dans l'étude.

2- Il est primordial de faire plusieurs analyses de données afin de déterminer celles qui sont anodines et celles qui ne le sont pas selon leur causalité et leur corrélation. Ce qui n'a pas été respecté dans ce cas d'études.
Par exemple, on peut remarquer que quand la température est égale à 70, selon que la pression soit égale à 50 ou à 100 ou 200. Cela ait un impact sur le dysfonctionnement de l'appareil. Toutefois, cette donnée a été supprimée en prétendant que "la pression est **quasiment** toujours égale à 200". Alors qu'il possible que cette donnée une information supplémentaire car elle **n'est pas TOUJOURS** égale à  200 mais quasiment.

3- Il est aussi important d'avoir des données obtenues à partir d'expériences faites dans des conditions similaires ou presque à celles du jour de décollage. En d'autre termes, des essais lorsque la température aurait été proche de 31°F. Ce qui n'a pas été le cas. En effet, la plus petite température du jeu de données est 57°F, pratiquement le double de 31°F, ce qui est aberrant.

4- En vue des remarques ci-dessus, la regression logistique a elle aussi retourné des résultats peu pertinents. 

5- Pour terminer, les données utilisées pour le prédicition sont au moins 10 plus volumineuses que celles utilisées en entrée du modéle de la regression logistique, ce qui est trés peu commun. Car souvent, les données utilisées pour la prévision représentent 20%-30% de l'ensemble des données.



