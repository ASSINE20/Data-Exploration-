# Ford GoBik-Trip Data Exploration

## by ASSINE Géraud


## Dataset

Ce dataset contient au total 183412 observations et 16 variables, dont certaines quantitatives et d'autres qualitatives. On peut trouver le dataset sur ce [lien](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)

## Summary of Findings

Dans l'exploration, je n'ai pas trouvé une très grande relation entre les deux variables quantitatives duration_sec et member_birth_year avec d'autres variables. Ce pendant, une relation utile sur laquelle on peut se fier est la relation entre la variable duration_sec et les trois autres variables qualitatives. La variable cible (duration_sec) a une distribution unimodale et est quasiment symétrique après la transformation du log10. Ce pendant, trois variables qualitatives (member_gender,user_type, bike_share_for_all_trip) ont chacune une relation avec cette variable duration_sec.

## Key Insights for Presentation

Pour la présentation je vais mettre l'accent sur l'impact des trois variables qualitatives sur la variable duration_sec.
- D'abord par la variable cible duration_sec, je vais appliquer la transformation du log10 sur cette variable et visualiser sa distribution.
- En suite, je vais présenter chacune des variable qualitative en relation avec la variable duration_sec, avec un graphe de vilon et un gaphe à points. Dans le graphe à points je vais introduire des couleurs différentes pour chaque groupe.
