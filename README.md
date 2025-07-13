# Airline Passenger Satisfaction Prediction

Ce projet a pour objectif de prédire la satisfaction des passagers d’une compagnie aérienne à partir de données réelles d’enquête, en utilisant des techniques d’apprentissage automatique.

##  Objectif

Développer un modèle de machine learning capable de classifier les passagers comme "satisfaits" ou "neutres/in­satisfaits" à partir de leurs caractéristiques de vol et de leurs évaluations de service.  
Ce projet vise aussi à identifier les facteurs influençant le plus la satisfaction client.

##  Outils et technologies

- Python 
- Bibliothèques : `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Modèles ML : 
  - Random Forest Classifier  
  - K-Nearest Neighbors (KNN)  
  - Decision Tree Classifier

##  Étapes du projet

1. **Exploration des données (EDA) 
   - Analyse des valeurs manquantes, outliers et distributions
   - Visualisation des corrélations et relations entre variables (heatmap, boxplots, scatterplots, countplots)

2. **Prétraitement des données  
   - Suppression des colonnes inutiles (`id`, `Unnamed: 0`)  
   - Traitement des valeurs manquantes  
   - Encodage des variables catégorielles (`OneHotEncoder`)  
   - Normalisation des variables numériques (`StandardScaler`)

3. **Entraînement des modèles  
  
   - Entraînement et évaluation des modèles (Random Forest, KNN, Decision Tree)  
   - Comparaison des performances avec `accuracy`, `rapport de classification`, `matrice de confusion`

4. **Analyse des résultats  
   - Identification des variables les plus importantes selon le modèle (feature importance)

## Résultats

- **Accuracy obtenue** : ~96%  
- Variables les plus influentes :  
  - Embarquement en ligne  
  - Wifi à bord  
  - Type de voyage (personnel ou business)

##  Données

Les jeux de données utilisés sont :  
- `train_airline.csv`  
- `test_airline.csv`  
Chaque observation correspond à un passager et inclut des informations comme l’âge, le type de voyage, la classe, le confort des sièges, etc.

##  Conclusion

Ce projet démontre l’efficacité des modèles de classification pour prédire la satisfaction des passagers. Il met également en lumière les services prioritaires à améliorer pour optimiser l’expérience client.



- LinkedIn : https://www.linkedin.com/in/ziane-zidi-2345372b4/  
- Email : zianezidi06@gmail.com
	
