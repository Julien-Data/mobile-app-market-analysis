# Mobile App Market Analysis

## 📌 Description du projet
Ce projet consiste en une **analyse des applications mobiles du Google Play Store**, visant à extraire des insights sur le comportement des utilisateurs et les revenus générés. 
L'objectif principal est de **comprendre les tendances du marché**, analyser la popularité et les notes par catégorie, et explorer les relations entre les différentes métriques (installations, prix, taille, type, etc.) pour identifier des opportunités et des leviers de performance.

Le projet est réalisé dans un **notebook Jupyter en Python**, avec des analyses univariées et bivariées ainsi que des tests d’hypothèses pour valider certaines observations.

---

## 🗂 Dataset
- **Source :** Kaggle  
- **Nom :** Google Play Store Apps  
- **Lien :** [https://www.kaggle.com/datasets/lava18/google-play-store-apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)  
- **Contenu :** Informations sur les applications (nom, catégorie, note, nombre d'avis, taille, installations, type, prix, genres, dernière mise à jour, version Android requise)

> ⚠️ Les données sont utilisées à des fins éducatives et analytiques. Le dataset original reste la propriété de Kaggle.

---

## 🧪 Outils et bibliothèques utilisés
- **Langage :** Python  
- **Notebook :** Jupyter Notebook  
- **Bibliothèques :** Pandas, NumPy, Matplotlib, Seaborn, Scipy  

---

## 🔍 Analyses réalisées
1. **Nettoyage des données**
   - Gestion des valeurs manquantes
   - Conversion des formats numériques
   - Standardisation des catégories et types

2. **Analyse univariée**
   - Distribution des notes, installations et prix
   - Répartition par catégorie et type (Free/Paid)

3. **Analyse bivariée**
   - Corrélation entre notes et installations
   - Relation prix ↔ installations
   - Comparaison des notes par catégorie

4. **Tests d’hypothèses**
   - Comparaison des notes moyennes entre apps gratuites et payantes
   - Analyse des différences entre catégories populaires

---

## 📊 Résultats clés / Insights
- Les **catégories les plus populaires** sont les jeux et outils de productivité.  
- Les **applications les mieux notées** ne sont pas nécessairement les plus installées.  
- Les applications **payantes ont tendance à avoir des notes légèrement supérieures**, mais pas toujours significatif statistiquement.  
- La **taille de l'application n’est pas fortement corrélée** avec le nombre d’installations.

---

## 🚀 Objectifs atteints
- Compréhension globale des tendances du marché des applications mobiles.  
- Identification de corrélations intéressantes entre métriques.  
- Application pratique de techniques de **nettoyage de données, visualisation, analyse statistique et tests d’hypothèses**.

---

## 🏗 Structure du projet

Étape 1 - Importation des librairies, chargement des fichiers et configuration visuelle

Étape 2 - Analyse exploratoire des fichiers

Étape 3 - Préparation et nettoyage des données

Étape 4 - Analyse univariée

Étape 5 - Analyses bivariées