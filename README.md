# 🛒 Nettoyage de données et analyse exploratoire

## 📌 Présentation du projet

Ce projet porte sur l'analyse d'un jeu de données de transactions e-commerce à l'aide de Python. L'objectif était de transformer des données brutes et incohérentes en informations stratégiques fiables grâce à un flux de travail complet d'analyse de données, incluant le nettoyage, l'analyse exploratoire (EDA) et la visualisation.

Ce projet a été réalisé dans le cadre de mon stage chez AnalystLab Africa.

---

## 🎯 Objectifs

- Évaluer et améliorer la qualité des données.
- Identifier les tendances des ventes et les habitudes d'achat des clients.
- Identifier les produits et les marchés les plus performants.
- Générer des informations stratégiques exploitables grâce à l'analyse des données.

## 🛠️ Technologies utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧹 Processus de nettoyage des données

### Gestion des valeurs manquantes

- Remplacement des valeurs manquantes de `CustomerID` par « Unknown » (Inconnu).
- Suppression des enregistrements dont la description du produit était manquante.

### Détection des doublons

- Identification et suppression des transactions en double.

### Validation des données

- Détection de valeurs négatives pour les colonnes `Quantity` (Quantité) et `UnitPrice` (Prix unitaire).
- Remplacement des quantités invalides par la médiane calculée pour chaque produit.

### Traitement des valeurs aberrantes

- Application de la méthode de l'écart interquartile (IQR).
- Suppression des observations extrêmes susceptibles de fausser l'analyse.

## 🔍 Principales conclusions

### Produits phares

Les articles de décoration et les produits saisonniers ont généré une part importante du chiffre d'affaires total.

### Saisonnalité des ventes

Les ventes ont considérablement augmenté au cours du dernier trimestre de l'année.

### Performance géographique

Le Royaume-Uni a généré la plus grande part du chiffre d'affaires.

## 📚 Compétences démontrées

- Nettoyage de données
- Validation de données
- Analyse exploratoire des données (EDA)
- Visualisation de données
- Génération d'informations stratégiques
