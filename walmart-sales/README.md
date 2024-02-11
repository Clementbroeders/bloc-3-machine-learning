# Walmart Sales Machine Learning

<img src="img/image.jpg" alt="Image" width="50%" height="50%">


## Introduction

Le service marketing de Walmart vous a demandé de construire un modèle d'apprentissage automatique capable d'estimer les ventes hebdomadaires dans leurs magasins, avec la meilleure précision possible sur les prévisions effectuées. Un tel modèle les aiderait à mieux comprendre comment les ventes sont influencées par les indicateurs économiques et pourrait être utilisé pour planifier les futures campagnes marketing.

Pour ce projet, j'ai travaillé avec un ensemble de données qui contient des informations sur les ventes hebdomadaires réalisées par différents magasins Walmart, ainsi que d'autres variables telles que le taux de chômage ou le prix du carburant, qui pourraient être utiles pour prédire le montant des ventes. 


## Clone du repo

Pour cloner le repo, utilisez la commande suivante :

`git clone https://github.com/Clementbroeders/walmart-sales-ml`


## Comment ça marche ?

Pour réaliser cette étude, Walmart nous a fourni une liste de 150 ventes réparties sur plusieurs magasins.

Ces ventes sont disponibles au chemin suivant : `src/Walmart_Store_sales.csv`

Nous utiliserons la régression linéaire, et plus particulièrement les modèles ridge et lasso.


## Etapes

Le notebook est entièrement automatisé et disponible à la racine du repo : `notebook.ipynb`

Une fois lancé, les modèles sont créés, puis enregistrés aux chemin suivant : `src/regressor_model.joblib`, `src/ridge_model.joblib`, `src/lasso_model.joblib`

Les résultats sont consutables dans le notebook.