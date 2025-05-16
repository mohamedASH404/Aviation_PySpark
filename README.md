# Analyse des Retards de Vols avec PySpark

## Description

Ce notebook PySpark analyse un jeu de données de vols afin de comprendre les retards.  
Il couvre notamment :

- La création de colonnes indicatrices (ex. : vol retardé ou non)
- Le calcul de statistiques agrégées (moyenne des retards, totaux par cause)
- L’utilisation de fenêtres pour calculer des pourcentages
- La visualisation des résultats avec Seaborn
- La manipulation avancée de DataFrames Spark (groupBy, agg, filter, etc.)

## Prérequis

- Apache Spark (PySpark) installé et configuré  
- Python 3.x  
- Bibliothèques Python suivantes installées :  
  - pandas  
  - seaborn  
  - matplotlib  

Pour installer les bibliothèques Python, utilisez :  
```bash
pip install pandas seaborn matplotlib
