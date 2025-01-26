# Analyse de la Qualité des Eaux en France 🇫🇷

Ce projet vise à évaluer la qualité des stations d'eau de surface en France en combinant des analyses biologiques et physico-chimiques, grâce à des données fournies par le **SANDRE** (Service d’Administration Nationale des Données et Référentiels sur l’Eau). L'objectif principal est d'identifier les paramètres influents dans la qualité de l'eau afin de mieux comprendre les facteurs déterminants de sa préservation.

---

## 🔍 Résumé du Projet

- **Problématique** : Comprendre les relations entre les caractéristiques physico-chimiques et l'état biologique des eaux.
- **Données Sources** :
    - **Hydrobiologiques** : Classement écologique des stations basé sur des macro-invertébrés (I2M2).
    - **Physico-chimiques** : Mesures telles que nitrates, DBO5, phosphore, oxygène dissous, etc.
    - **Stations** : Localisation, type (eau de surface ou souterraine), informations administratives.
- **Méthodologie** : Prétraitement des données (nettoyage, clustering), intégration de sources multiples, et modélisation via l'algorithme XGBoost.
- **Résultats** : Analyse des principaux facteurs influençant la qualité biologique à travers différents ensembles de stations hydrologiques.

---

## 📊 Structure des Données

- **Sources des données** : SANDRE, un système national standardisé et fiable.
- **Nettoyage & Transformation** : Traitement des valeurs manquantes, standardisation, et regroupement des stations en clusters pour améliorer les analyses.
- **Clustering et Modélisation** : Intégration des paramètres physico-chimiques dans des modèles prédictifs, permettant une meilleure compréhension des relations entre ces paramètres et les indices biologiques.

----

## 🚀 Principaux Résultats

- Mise en évidence des **paramètres physico-chimiques les plus influents** dans l'état écologique des eaux.
- Modélisation robuste avec l'algorithme **XGBoost**, offrant des résultats cohérents sur différents clusters de stations.

---

## 📘 En savoir plus

Pour une description détaillée des méthodes et des résultats, veuillez consulter le [rapport complet](https://github.com/ClemWasChoosen/Water-ML-Analysis/blob/main/Rapport-JAIDANE-OBERHAUSER.pdf).

---

## 🛠️ Technologies Utilisées

- **Langages** : Python
- **Librairies** : pandas, numpy, XGBoost, scikit-learn
- **Visualisation** : seaborn, matplotlib
- **Données** : Jeux de données SANDRE (hydrobiologiques, physico-chimiques, stations)


## 🧑‍💻 Auteurs

- Chaïma JAIDANE
- Clément OBERHAUSER
