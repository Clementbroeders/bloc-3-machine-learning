# Uber Insights NYC Machine Learning

<img src="img/image.jpg" alt="Image" width="50%" height="50%">


## Introduction

L'un des principaux problèmes que l'équipe d'Uber a identifiés est que parfois, les chauffeurs ne se trouvent pas à proximité lorsque les utilisateurs ont besoin d'eux. Par exemple, un utilisateur pourrait se trouver dans le quartier financier de San Francisco tandis que les chauffeurs Uber recherchent des clients dans le quartier de Castro.

Même si les deux quartiers ne sont pas très éloignés, les utilisateurs devraient tout de même attendre 10 à 15 minutes avant d'être pris en charge, ce qui est trop long. Les recherches d'Uber montrent que les utilisateurs acceptent d'attendre entre 5 et 7 minutes, sinon ils annulent leur trajet.

Par conséquent, l'équipe de data d'Uber souhaite travailler sur un projet où leur application recommanderait des zones chaudes dans les grandes villes à tout moment de la journée.


## Clone du repo

Pour cloner le repo, utilisez la commande suivante :

`git clone https://github.com/Clementbroeders/uber-insights-nyc-ml.git`


## Comment ça marche ?

Pour réaliser cette étude, Uber nous a fourni des données sur l'année 2014, disponible au lien suivant :

[Uber data 2014](https://full-stack-bigdata-datasets.s3.eu-west-3.amazonaws.com/Machine+Learning+non+Supervis%C3%A9/Projects/uber-trip-data.zip)

Nous utilisons 2 algorithmes de machine learning afin de déterminer les hot-zones :

1) KMeans : algorithme de regroupement pour identifier des hot-zones en fonction de la densité de courses.

2) DBscan : algorithme basé sur la densité pour détecter des zones de forte concentration de courses en ignorant celles non pertinentes.


## Etapes

Le notebook est entièrement automatisé et disponible à la racine du repo : `notebook.ipynb`

Une fois lancé, le notebook va créer 2 fichiers de résultats :

1) `plotly/resultat_kmeans.html`

2) `plotly/resultat_dbscan.html`

Les données `uber-trip-data` sont téléchargées, puis enregistrées dans le dossier `src`. N'oubliez pas de les supprimer pour réduire l'impact sur votre stockage.