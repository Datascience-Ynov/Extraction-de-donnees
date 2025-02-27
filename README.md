# Extraction de KPI à partir des Logs

## Contexte du Projet

Ce projet vise à analyser les logs d'utilisation d'un outil de Matching pour extraire des Indicateurs Clés de Performance (KPI). L'objectif est d'évaluer l'utilisation de l'outil et de recueillir des retours utilisateurs pour améliorer l'expérience.

Les logs contiennent des informations sur les recherches de jobs, les feedbacks des utilisateurs et d'autres actions pertinentes. Ce projet se concentre sur l'extraction et l'analyse de ces données pour en tirer des conclusions exploitables.

## Objectifs

1. **Chargement des Données** : Importer les logs à partir d'un fichier Excel.
2. **Prétraitement des Données** : Nettoyer et préparer les données pour l'analyse.
3. **Extraction des KPI** :
   - Nombre total de recherches effectuées.
   - Nombre d'erreurs rencontrées.
   - Nombre de candidats uniques recherchés.
   - Nombre moyen d'offres d'emploi retournées par candidat.
4. **Analyse des Feedbacks** :
   - Répartition des likes et dislikes.
   - Extraction des raisons des dislikes.
5. **Visualisation des Résultats** :
   - Créer des graphiques pour illustrer les KPI et les feedbacks.

## Technologies Utilisées

- **Langage** : Python
- **Bibliothèques** :
  - **Pandas** : Pour la manipulation et l'analyse des données.
  - **Matplotlib** : Pour la visualisation des données.
  - **OpenPyXL** : Pour la lecture des fichiers Excel.
  - **JSON** : Pour le traitement des données sous format JSON.

## Étapes du Projet

### 1. Chargement des Données
- Chargement du dataset à partir de `logs_matching.xlsx`.
- Affichage des informations et des premières lignes pour vérifier la structure des données.

### 2. Prétraitement des Données
- Transformation des colonnes `customDimensions` et `customMeasurements` en dictionnaires JSON.
- Nettoyage des valeurs manquantes et conversion des types de données.

### 3. Extraction des KPI
- Calcul du **nombre total de recherches** effectuées.
- Identification des **erreurs** sur les recherches de jobs.
- Détermination du **nombre de candidats uniques**.
- Calcul du **nombre moyen d'offres retournées par candidat**.

### 4. Analyse des Feedbacks
- Extraction des feedbacks reçus pour mesurer la satisfaction des utilisateurs.
- Répartition des feedbacks en likes, dislikes et neutres.
- Analyse des raisons des dislikes.

### 5. Visualisation des Résultats
- Création de graphiques pour illustrer la répartition des feedbacks.
- Visualisation des raisons des dislikes et autres KPI importants.

## Résultats Obtenus

- **Nombre total de recherches** : 2220
- **Nombre d'erreurs de recherche** : 498
- **Nombre de candidats uniques** : 275
- **Nombre moyen d'offres par candidat** : 33.88
- **Répartition des feedbacks** :
  - Likes : 38
  - Dislikes : 48
  - Neutres : 15

## Comment Utiliser ce Projet

1. **Cloner le dépôt** :
   ```bash
   git clone git@github.com:Mourad2511/extraction-kpi.git
   cd extraction-kpi

2. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt

3. **Exécuter le script principal** :
   ```bash
   cliquer sur Run pour éxécuter la cellule du notebook, ou Run all pour toutes les cellules


### Auteur
Nom : **AMOUSSA Mourad**

Contact : [mourad1.amoussa@outlook.com]

LinkedIn : [www.linkedin.com/in/mourad-amoussa]

GitHub : [https://github.com/Mourad2511]
