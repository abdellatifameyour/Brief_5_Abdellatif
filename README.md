# Projet d’Analyse du Catalogue Netflix 🎬📊
## 📝 Objectifs du projet

1. Explorer et analyser le dataset Netflix avec Python et Pandas  
2. Produire des visualisations claires et pertinentes avec Matplotlib et Seaborn  
3. Répondre à des questions métier liées aux contenus  
4. Identifier les tendances et insights clés du catalogue  
5. Préparer les données pour un futur dashboard interactif avec Power BI  


## 🗂️ Étapes principales

### 1️⃣ Exploration des données (EDA)
**Objectif :** comprendre le dataset avant nettoyage ou transformation  

**Actions réalisées :**  
- Vérification de la structure et des types de données (`info()`, `describe()`)  
- Identification des colonnes avec valeurs manquantes (ex. `director`, `country`, `rating`)  
- Analyse des distributions et fréquences des variables (ex. films vs séries, genres, pays)  
- Identification des doublons et anomalies  
- Visualisation rapide pour détecter des patterns (histogrammes, countplots, boxplots)  


### 2️⃣ Préparation et nettoyage des données
**Objectif :** préparer le dataset pour l’analyse finale et le futur dashboard  

**Actions réalisées :**  
- Gestion des valeurs manquantes : suppression ou remplacement par `"Inconnu"`  
- Suppression des doublons  
- Transformation des colonnes multi-valeurs (`country`, `listed_in`)  
- Création de colonnes dérivées : année, mois, jour d’ajout (`date_added`), durée en minutes  
- Harmonisation des formats : dates, durées, type de contenu  

### 3️⃣ Visualisations et analyse métier
**Objectif :** répondre aux questions métier et identifier des tendances  

**Questions clés traitées :**  
- Répartition des contenus par classification d’âge (`rating`)  
- Proportion de films vs séries (`type`)  
- Nombre de contenus ajoutés chaque année (`year_added`)  
- Évolution du catalogue : films vs séries par année  
- Nombre de séries de 2011 à 2021  
- Nombre de productions par pays  
- Nombre de productions par pays et par classification d’âge  
- Analyse des genres (`listed_in`)  
- Identification des contenus les plus fréquents par genre ou catégorie  
