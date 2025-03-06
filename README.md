# BTC Price Analysis Dashboard

## Description du Projet
Ce projet vise à analyser et visualiser l'évolution du prix du Bitcoin (₿) à travers un tableau de bord interactif conçu avec Power BI. Les données proviennent d'un fichier CSV issu de Kaggle, contenant des enregistrements de prix à la minute depuis 2012. L'objectif est d'explorer les tendances du marché, les fluctuations de prix et d'offrir une représentation claire des variations du Bitcoin sur plusieurs années.

## Dashboard
![BTC Dashboard](https://github.com/sbocquetpro/BTC-Price-Analysis/blob/main/BTC%20Analysis%20Dashboard.png)

## Objectifs du Projet
- Créer un dashboard Power BI clair et interactif
- Analyser l'évolution du prix du Bitcoin sur plusieurs années
- Identifier les tendances de marché 
- Mettre en avant les variations quotidiennes, mensuelles et annuelles

## Données Utilisées
- **Source** : Fichier CSV `btcusd_1-min_data.csv` provenant de [Kaggle](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)
- **Contenu** : Prix du BTC (open, high, low, close) et volume des transactions
- **Période couverte** : De 2012 au 17/02/2025

## Technologies Utilisées
- **Power BI** : Pour la visualisation des données
- **DAX & Langage M** : Pour la transformation et l'analyse des données
- **Git/GitHub** : Pour le versioning du projet

## Défis Rencontrés
- **Taille des données** : Le fichier CSV était volumineux (plus de 350 Mo), ce qui a nécessité une optimisation des requêtes et un filtrage des données.
- **Nettoyage des données** : Certaines valeurs manquantes et incohérences ont été identifiées et corrigées.
- **Optimisation du dashboard** : Il a fallu réduire le temps de chargement des visualisations en utilisant des agrégations et en optimisant les relations entre tables.
- **Problème de variation infinie** : Certains endroits du tableau de bord affichent une variation de prix "+Infinity" en raison des valeurs manquantes dans le dataset.

## Ce que J'ai Fait
- Création d'une **dimension date** dans l'onglet modélisation
- Reconstitution de toutes les **time frames** en partant de 1 minute
- Transformation du **timestamp** en format lisible avec le **langage M**
- Travail sur les **mesures DAX** pour l'analyse des tendances
- Mise en place de nombreuses **visualisations interactives** avec du **conditional formatting**
- Ajout d'éléments graphiques et esthétiques avec l'insertion de formes

## Résultat
Le tableau de bord final permet une analyse dynamique du prix du Bitcoin avec des KPIs clés, un graphique de l'évolution des prix, et des filtres interactifs pour explorer différentes périodes.

## Prochaines étapes
- Ajouter de nouvelles sources de données pour enrichir l'analyse
- Intégrer des indicateurs d'analyse technique (ex. : moyennes mobiles, RSI)
- Créer des prédictions à l'aide du machine learning


