# Projet 4 - Prévision des émissions de CO2 et de la consommation énergétique des bâtiments non résidentiels

## Contexte

Vous travaillez pour la ville de Seattle, dans le cadre de son objectif de devenir une ville neutre en émissions de carbone d'ici 2050. Votre équipe s'intéresse particulièrement à la consommation et aux émissions des bâtiments non destinés à l'habitation.

En 2016, des relevés ont été effectués par les agents de la ville. Cependant, ces relevés sont coûteux à obtenir. Vous êtes missionné pour prédire les émissions de CO2 et la consommation totale d’énergie pour des bâtiments non résidentiels pour lesquels ces données n'ont pas encore été mesurées. 

La prédiction se basera sur les données structurelles des bâtiments : taille, usage, date de construction, situation géographique, etc. Vous devez aussi évaluer l’utilité de l’"ENERGY STAR Score" pour la prédiction des émissions.

## Objectifs

1. **Analyse exploratoire des données** : Nettoyage et préparation des données avant la modélisation.
2. **Modélisation des prédictions** :
   - Prédire les émissions de CO2.
   - Prédire la consommation totale d'énergie.
3. **Évaluation des modèles** : Test des performances de différents modèles de Machine Learning.
4. **Optimisation des modèles** : Validation croisée et optimisation des hyperparamètres.
5. **Évaluation de l'impact de l'ENERGY STAR Score**.

## Méthodes utilisées

Les modèles de Machine Learning testés sont :

- **Régression linéaire** : Un modèle simple pour tester la linéarité des relations.
- **Random Forest** : Un modèle d'ensemble basé sur des arbres de décision, robuste aux surajustements.
- **XGBoost** : Un modèle basé sur le boosting de gradient pour de meilleures performances.
- **Support Vector Machine (SVM)** : Utilisé pour classifier et régression avec des marges maximales.

Les transformations des données incluent la normalisation, les transformations logarithmiques et la gestion des variables catégorielles.

## Structure du projet

1. **Notebook d'analyse exploratoire** : Ce notebook contient l'exploration et le nettoyage des données, ainsi que des visualisations pour mieux comprendre les relations dans les données.
   - `Sole_Johanna_1_notebook_exploratoire_122024.ipynb`
   
2. **Notebooks de modélisation** : Des notebooks distincts pour les tests de modèles de prédiction des émissions de CO2 et de la consommation d’énergie.
   - `Sole_Johanna_2_notebook_prediction_122024.ipynb` (Cible 1 : **TotalGHGEmissions**)
   - `Sole_Johanna_3_notebook_prediction_122024.ipynb` (Cible 2 : **SiteEnergyUse(kBtu)**)

3. **Présentation** : Un fichier PDF présentant les résultats de l'analyse et de la modélisation.
   - `Johanna_Sole_4_presentation_122024.pdf`

## Résultats attendus

- Un modèle performant capable de prédire avec précision les émissions de CO2 et la consommation énergétique des bâtiments.
- Une analyse de l'impact de l'ENERGY STAR Score sur la précision des prédictions.

## Données

Les données utilisées dans ce projet proviennent de **Building Energy Benchmarking Data (2015-Present)**, disponibles sur le site officiel de la ville de Seattle. Vous pouvez accéder aux données et à la description des variables sur le [site officiel](https://data.seattle.gov/Built-Environment/Building-Energy-Benchmarking-Data-2015-Present/teqw-tu6e/about_data).


