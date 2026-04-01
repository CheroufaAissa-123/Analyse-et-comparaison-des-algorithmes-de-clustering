# Analyse et comparaison des algorithmes de clustering

## Description
Ce projet compare trois algorithmes de clustering non supervisé appliqués au dataset Iris :
- K-Means
- GMM
- DBSCAN

L’objectif est d’analyser leur fonctionnement, de tester leurs hyperparamètres et de comparer leurs résultats.

## Dataset
Le projet utilise le dataset Iris, composé de 150 observations et 4 variables numériques.
Les données ont été standardisées avant l’application des modèles. :contentReference[oaicite:0]{index=0}

## Résultats principaux
- **K-Means** : meilleur choix avec **K = 3**
- **GMM** : bon compromis avec **K = 4**
- **DBSCAN** : meilleur équilibre avec **eps = 0.8** et **min_samples = 5** :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Conclusion
K-Means est simple et rapide, GMM est plus flexible, et DBSCAN permet de détecter le bruit. Le choix de l’algorithme dépend donc de la structure des données et de l’objectif de l’analyse. :contentReference[oaicite:4]{index=4}

## Technologies
Python, NumPy, Pandas, Matplotlib, Scikit-learn, Jupyter Notebook
