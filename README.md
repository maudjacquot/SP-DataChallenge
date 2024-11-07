# Data Challenge

## Présentation 
Ce repository contient le code pour un problème de regression et de classification. Les données sont disponibles sur les Kaggle suivants: 
* Regression : [Page de la compétition Kaggle - NYC taxis tips](https://www.kaggle.com/competitions/nyc-taxis-tips/overview)
* Classification : [Page de la compétition Kaggle - Forest Cover Type](https://www.kaggle.com/competitions/forest-cover-type-orsay/overview)


## Chemin vers les données 
Dans les deux notebook que contient ce repository, il faut préciser le chemin vers les données dans les 2ème et 3ème cellules pour ``regression.ipynb``et dans la 2ème cellule pour ``classification.ipynb``.

## Regression 
Ce projet porte sur la prédiction des pourboires pour des courses de taxi effectuées à New York. Le jeu de données comprend un échantillon de 100 000 courses de taxis réalisées en janvier 2024, pour lesquelles le montant des pourboires (``tip_amount``) est connu. Chaque course est caractérisée par plusieurs variables, telles que les coordonnées géographiques de départ et d'arrivée (``PU_location_lat``, ``PU_location_lon``, ``DO_location_lat`` et ``DO_location_lon``), la distance parcourue (``Trip_distance``), les dates et heures de début et de fin (``tpep_pickup_datetime`` et ``tpep_dropoff_datetime``), et le montant total de la course (``Fare_amount``).

Le jeu de données contient 19 variables explicatives, qualitatives et quantitatives.
Le jeu de données d'entraînement train.parquet inclut la variable cible, tandis que le fichier test.parquet ne la contient pas. Les soumissions sur Kaggle sont évaluées suivant le score R² (coefficient de détermination).

## Classification 
Cette étude a pour but la prédiction du type de végétation forestière de différentes parcelles en se basant sur des caractéristiques cartographiques (altitude, inclinaison, type de sol…). Les données traitées correspondent à environ 581 000 parcelles de taille 30m par 30m situées dans le Colorado (Roosevelt National Forest). Pour chacune de ces parcelles, on connaît le type de végétation forestière (7 modalités).

Les données analysées proviennent de la Forêt Nationale de Roosevelt, située dans le Colorado, et concernent différentes caractéristiques topographiques, hydrologiques, routières et environnementales de parcelles forestières. Ces variables sont utilisées pour prédire le type de végétation forestière sur chaque parcelle de 30m x 30m. Pour chacune de ces dernières, on connaît le type de végétation forestière qui lui même a 7 modalités: ``1: Spruce/Fir``, ``2: Lodgepole Pine``, ``3: Ponderosa Pine``, ``4: Cottonwood/Willow``, ``5: Aspen``, ``6: Douglas-fir`` et ``7: Krummholz``.

