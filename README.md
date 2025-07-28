# 📊 Prédiction par Régression SVR (Support Vector Regression)

Ce projet de machine learning vise à prédire une variable cible continue à partir de plusieurs caractéristiques (features) en utilisant un modèle **SVR (Support Vector Regression)**. L’objectif est d'obtenir des prédictions les plus précises possibles grâce à une bonne préparation des données et à un entraînement rigoureux.

---

## 🧰 Outils et bibliothèques utilisés

- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn (`SVR`, `train_test_split`, `StandardScaler`, etc.)

---

## 🔄 Étapes du projet

### 1. Chargement des données
Les données sont importées depuis un fichier `.csv` à l’aide de pandas.

### 2. Prétraitement
- Suppression des doublons
- Détection et traitement des valeurs aberrantes via les boxplots et l'IQR
- Normalisation des features (StandardScaler)

### 3. Séparation des données
Les données ont été divisées en :
- **X** : variables explicatives
- **y** : variable cible à prédire  
Puis séparées en **jeu d'entraînement** et **jeu de test** (80/20).

### 4. Modélisation avec SVR
- Entraînement d’un modèle SVR avec le jeu d'entraînement
- Prédiction sur le jeu de test

### 5. Évaluation des performances
Les métriques utilisées :
- **MAE (Mean Absolute Error)** : 3.3674
- **MSE (Mean Squared Error)** : 56.0729
- **RMSE (Root Mean Squared Error)** : 7.4882
- **R² (Coefficient de détermination)** : 0.8801

---

## 📈 Interprétation des résultats

- Le score **R² = 0.88** indique que le modèle explique environ **88 %** de la variance de la variable cible.
- Les erreurs (MAE, MSE, RMSE) sont relativement faibles, ce qui montre que les prédictions sont **proches des valeurs réelles**.

---

## ✅ Suggestions d'amélioration

- **Optimisation des hyperparamètres** du modèle SVR (`C`, `gamma`, `epsilon`)
- **Test d'autres algorithmes** de régression (Random Forest, Gradient Boosting, etc.)
- **Feature Engineering** : création de nouvelles variables pertinentes
- **Cross-validation** pour mieux évaluer la performance
- **Ensembles de modèles** pour améliorer la robustesse

---

## 👨‍💻 Auteur

Projet réalisé par **Cheikh Niang** dans le cadre de sa formation en **Data Science / Machine Learning**.

---

## 📂 Structure du projet

├── data/
│ └── dataset.csv
├── notebook/
│ └── regression_SVR.ipynb
├── README.md

yaml
Copier
Modifier

---

## 🚀 Objectif

Ce projet a été réalisé dans un but d’apprentissage et de maîtrise des techniques de régression, en particulier du modèle **SVR**, ainsi que de l’analyse des performances à l’aide de métriques classiques.

---
