# Prévision des émissions de CO2 et de la consommation énergétique des bâtiments non résidentiels

## Contexte

Ce projet s’inscrit dans l’objectif de la ville de Seattle de devenir neutre en émissions de carbone d’ici 2050. L’analyse porte sur la consommation énergétique et les émissions de CO2 des bâtiments non résidentiels.

Les relevés de 2016, bien que complets, sont coûteux à obtenir. Le projet vise donc à prédire ces données pour des bâtiments non mesurés, à partir de leurs caractéristiques structurelles (taille, usage, date de construction, localisation, etc.).

L’utilité de l’**ENERGY STAR Score** sera également évaluée dans le cadre des prédictions.

## Objectifs

- Effectuer une analyse exploratoire des données : nettoyage, préparation et visualisation  
- Modéliser les prédictions des émissions de CO2 et de la consommation énergétique totale  
- Tester plusieurs modèles de Machine Learning :  
  - Régression linéaire  
  - Random Forest  
  - XGBoost  
  - Support Vector Machine (SVM)  
- Optimiser les modèles par validation croisée et réglage des hyperparamètres  
- Évaluer l’impact de l’ENERGY STAR Score sur la qualité des prédictions  

## Méthodes utilisées

- Nettoyage et préparation des données, incluant normalisation, transformations logarithmiques et encodage des variables catégorielles  
- Mise en œuvre de modèles supervisés pour régression  
- Analyse comparative des performances des modèles  

## Structure du projet

- **Notebook d’analyse exploratoire :**  
  `Sole_Johanna_1_notebook_exploratoire_122024.ipynb`  
- **Notebooks de modélisation :**  
  - `Sole_Johanna_2_notebook_prediction_122024.ipynb` (Cible 1 : TotalGHGEmissions)  
  - `Sole_Johanna_3_notebook_prediction_122024.ipynb` (Cible 2 : SiteEnergyUse(kBtu))  
- **Présentation des résultats :**  
  `Johanna_Sole_4_presentation_122024.pdf`  

## Données

Les données proviennent du **Building Energy Benchmarking Data (2015-Present)**, accessibles via le site officiel de la ville de Seattle, avec documentation complète des variables.

## Résultats attendus

- Modèle prédictif performant des émissions de CO2 et de la consommation énergétique des bâtiments  
- Analyse détaillée de l’apport de l’ENERGY STAR Score dans la précision des prédictions  

## Auteur

Johanna Solé  
Projet réalisé dans le cadre d’une formation Data Scientist.

## Données

Les données utilisées dans ce projet proviennent de **Building Energy Benchmarking Data (2015-Present)**, disponibles sur le site officiel de la ville de Seattle. Vous pouvez accéder aux données et à la description des variables sur le [site officiel](https://data.seattle.gov/Built-Environment/Building-Energy-Benchmarking-Data-2015-Present/teqw-tu6e/about_data).


