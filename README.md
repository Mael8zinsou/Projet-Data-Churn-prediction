# Projet-Data-Churn-prediction

## 🎯 Objectif

Ce projet vise à **prédire l’attrition (churn)** des clients d’un opérateur télécom et à **visualiser les résultats** pour :

* Identifier les **profils clients à risque**
* Mettre en évidence les **leviers de rétention**

Le tout en utilisant **Python** pour la modélisation et **Power BI** pour l’analyse visuelle.

---

## 🛠️ Étapes du projet

### 1. Préparation des données

* Nettoyage et transformation du dataset **Telco Customer Churn**
* Encodage des variables catégorielles (type de contrat, service internet, méthode de paiement, etc.)
* Sélection des variables pertinentes pour la prédiction

### 2. Modélisation

* Entraînement de plusieurs modèles de machine learning :
  `Régression Logistique`, `Random Forest`, `XGBoost`
* Évaluation des performances via **précision**, **rappel**, **score F1**
* Génération des **probabilités de churn** pour chaque client

### 3. Export des résultats

* Création d’un fichier CSV avec :

  * Prédiction (churn ou non)
  * Probabilité de churn
  * Données explicatives associées

### 4. Visualisation dans Power BI

* Import du fichier CSV dans **Power BI Desktop**
* Transformation de certaines colonnes (ex : booléennes → catégorielles)
* Création de visuels interactifs pour l’exploration :

  * 📊 Taux de churn par type de contrat
  * 📡 Taux de churn par type d’internet
  * 💳 Taux de churn par méthode de paiement
  * 📈 Distribution des probabilités de churn
  * ⚠️ Segmentation des clients à risque
  * 🔥 Carte de chaleur croisant plusieurs facteurs (contrat x internet)

---

## ✅ Résultats

* Identification claire des **segments à risque**
  *(ex : clients en contrat “Month-to-month” avec fibre optique)*
* Mise en lumière des **facteurs influençant le churn**
* Dashboard interactif permettant d’**explorer dynamiquement les profils à risque**

---

## 📦 Prérequis

* Python 3.x (avec `pandas`, `scikit-learn`, `xgboost`, etc.)
* Power BI Desktop (gratuit)
* Dataset : **Telco Customer Churn**

---

## 🚀 Utilisation

1. Exécuter le notebook Python pour entraîner le modèle et générer le fichier CSV
2. Ouvrir **Power BI Desktop** et importer le fichier CSV
3. Reproduire ou personnaliser les visuels décrits dans le projet

---

## 👤 Auteur

Projet réalisé en solo par **\[Maël Mike ZINSOU]**
*(Master 1 Data Science [actu])*