# Thermodynamic Separation Modelling

Ce projet de science des données applique des techniques d'apprentissage automatique (Machine Learning) pour modéliser et analyser la séparation thermodynamique à partir de données expérimentales ou simulées.

## 📋 Table des matières
1. [Aperçu du projet](#aperçu-du-projet)
2. [Fonctionnalités](#fonctionnalités)
3. [Structure du projet](#structure-du-projet)
4. [Prérequis et Installation](#prérequis-et-installation)
5. [Utilisation](#utilisation)
6. [Méthodologie](#méthodologie)

---

## 🔬 Aperçu du projet
Le projet met en œuvre un pipeline complet de traitement de données et de modélisation prédictive en Python :
* **Exploration des données :** Chargement des jeux de données (fichiers CSV), analyse des valeurs manquantes et génération de statistiques descriptives.
* **Nettoyage et ingénierie des caractéristiques :** Détection et suppression des valeurs aberrantes (telles que les températures de plateau anormalement basses) à l'aide de boîtes à moustaches (*Boxplots*) et analyse des corrélations via une matrice de corrélation (*Heatmap*).
* **Modélisation prédictive :** Entraînement et évaluation d'un modèle de régression linéaire en utilisant la bibliothèque `scikit-learn` sur les données nettoyées.

---

## ✨ Fonctionnalités
* Pipeline de prétraitement reproductible.
* Visualisations statistiques et graphiques (matrice de corrélation, détection d'outliers).
* Modèle de régression linéaire optimisé pour la prédiction thermodynamique.

---

## 🛠️ Prérequis et Installation

Assurez-vous d'avoir Python installé sur votre machine. Installez ensuite les bibliothèques nécessaires à l'aide de la commande suivante :

