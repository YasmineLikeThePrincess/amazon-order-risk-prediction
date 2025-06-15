# Analyse des commandes à risque Amazon – Modélisation et prédiction par Machine Learning
<p align="center">
  <img src="https://tse2.mm.bing.net/th?id=OIP.RW4mrDzlNTg10qxa9bF-1wHaFL&r=0&pid=Api" alt="Page de garde - Mémoire" width="600"/>
</p>


## 📘 Contexte

Ce dépôt contient le code source et les ressources du mémoire de fin d’année réalisé dans le cadre du Master Data & IA.  
L’objectif est d’analyser les déterminants des commandes à risque sur Amazon et de construire un modèle de machine learning capable de prédire les annulations.

## 🧠 Objectifs

- Identifier les variables influençant les commandes annulées ou refusées
- Construire des modèles prédictifs (Random Forest, XGBoost)
- Optimiser les performances en réduisant les fausses alertes
- Interpréter les résultats via des analyses visuelles et statistiques

## 📂 Données

Les données utilisées dans ce projet proviennent de Kaggle :  
👉 [Amazon Order Dataset – Kaggle]([https://www.kaggle.com/datasets/nom-du-dataset](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data?resource=download))

  ## 📊 Technologies utilisées

- Python (Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub

## 📈 Modèles utilisés

- Random Forest Classifier
- XGBoost Classifier
- Métriques : accuracy, precision, recall, F1-score, courbe ROC

## 🔍 Résultats clés

- Le modèle atteint un recall élevé sur les cas à risque, tout en limitant les faux positifs.
- Analyse détaillée des variables les plus discriminantes (catégorie produit, montant, région…).
