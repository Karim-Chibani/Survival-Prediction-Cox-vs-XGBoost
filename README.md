# 🫀 Heart Failure Survival Analysis: Cox vs XGBoost

## 📌 Présentation du Projet
Ce projet est réalisé dans le cadre de mon **Master 2**. L'objectif est de prédire la survie des patients atteints d'insuffisance cardiaque en comparant deux approches majeures :
1. **Modèle statistique classique** : Modèle à risques proportionnels de **Cox**.
2. **Approche Machine Learning** : **XGBoost Survival** (Gradient Boosting).

## 📊 Résultats Principaux
L'étude montre une amélioration significative de la performance en passant du modèle statistique au Machine Learning :
* **C-index (Cox) :** 0.741
* **C-index (XGBoost) :** 0.886

### 🔍 Key Findings (Découvertes Clés)
* La **créatinine sérique** et la **fraction d'éjection** sont les prédicteurs les plus influents sur la survie.
* Une augmentation d'une unité de créatinine sérique augmente le risque de décès de **38%** (selon le Hazard Ratio du modèle de Cox).

## 🛠️ Technologies Utilisées
* **Langage** : Python 3
* **Librairies** : 
    * `lifelines` (pour l'analyse de survie et le modèle de Cox)
    * `xgboost` (pour le modèle de survie avancé)
    * `pandas`, `numpy` (traitement des données)
    * `seaborn`, `matplotlib` (visualisation)

## 📁 Structure du Repository
* `Survival_Analysis.ipynb` : Le Notebook complet avec code et interprétations.
* `heart_failure_clinical_records_dataset.csv` : Le jeu de données utilisé.

## 🚀 Comment l'utiliser
1. Cloner le projet : `git clone https://github.com/Karim-Chibani/Survival-Prediction-Cox-vs-XGBoost.git`
2. Installer les dépendances : `pip install lifelines xgboost pandas matplotlib seaborn`
3. Lancer le Notebook dans Jupyter ou Google Colab.
