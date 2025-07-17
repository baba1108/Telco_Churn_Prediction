# Telco_Churn_Prediction
Ce projet est une application interactive développée avec Streamlit pour prédire le risque de churn (désabonnement) des clients d’un opérateur télécom. Il repose sur des techniques avancées de data science, de prétraitement, et de machine learning appliquées à un jeu de données réel.
# 📊 Telco Churn Prediction Dashboard

![Streamlit](https://img.shields.io/badge/Streamlit-%F0%9F%9A%80-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

Application Streamlit interactive permettant de prédire le risque de désabonnement (churn) des clients d’un opérateur télécom à partir d’un jeu de données réel.

---

## 🗂 Sommaire

- [🔍 Fonctionnalités](#-fonctionnalités)
- [🧠 Modèle de Machine Learning](#-modèle-de-machine-learning)
- [📁 Jeu de données](#-jeu-de-données)
- [🚀 Installation et lancement](#-installation-et-lancement)
- [📸 Aperçu](#-aperçu)
- [🛠️ Technologies utilisées](#️-technologies-utilisées)

---

## 🔍 Fonctionnalités

- Vue d’ensemble des indicateurs de churn
- Visualisation des profils clients churners
- Évaluation du modèle (matrice de confusion, AUC, F1-score)
- Analyse des variables les plus influentes
- Simulation personnalisée de churn pour un nouveau client
- Exploration de cas de clients ayant churné

---

## 🧠 Modèle de Machine Learning

- **Random Forest Classifier**
- Rééquilibrage des classes avec **SMOTE**
- Évaluation via :
  - AUC-ROC
  - Matrice de confusion
  - Classification report (F1, précision, rappel)

---

## 📁 Jeu de données

- **Telco Customer Churn** *(IBM Watson Analytics)*
- Fichier : `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Variables : contrat, services, méthode de paiement, support, etc.
- Cible : `Churn` (Oui/Non)

---

## 🚀 Installation et lancement

### ✅ 1. Cloner le projet

```bash
git clone https://github.com/baba1108/telco-churn-dashboard.git
cd telco-churn-dashboard
