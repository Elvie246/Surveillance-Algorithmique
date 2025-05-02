# Projet Scinetifique d'Initiation à la Recherche - Surveillance Algorithmique

## Description du projet

Ce projet de recherche a pour objectif de développer et d'évaluer un modèle de reconnaissance de surveillance vidéos en utilisant des datasets de scènes provenant de la vie réelle. Le modèle utilise des techniques de traitement d'images et de vision par ordinateur pour analyser des vidéos et détecter des événements violents.

Le dataset utilisé dans ce projet comprend deux sources principales :

1. **Real Life Violence Dataset** : Ce dataset contient des vidéos annotées comprenant des scènes de violence provenant de la vie réelle.
2. **Real Life Violence Situations** : Ce dataset comprend des informations sur les différentes situations dans lesquelles la violence peut survenir, ainsi que des contextes sociaux et environnementaux.

Les objectifs principaux du projet incluent :
- La préparation et l'exploration des données.
- La création et l'entraînement de modèles pour la reconnaissance de la violence.
- L'évaluation des performances du modèle sur un ensemble de test.

L'objectif principal de cette recherche est de développer un modèle de machine learning capable de détecter des scènes violentes dans des vidéos. Le projet se divise en plusieurs étapes :

1. **Prétraitement des données** : Nettoyage et transformation des données pour les rendre exploitables par un modèle de machine learning.
2. **Exploration des données** : Analyse des caractéristiques des vidéos et des situations de violence pour comprendre les relations entre les différentes variables.
3. **Développement du modèle** : Création de modèles de vision par ordinateur pour détecter la violence dans les vidéos. Nous testerons différents types de modèles, y compris les réseaux neuronaux convolutifs (CNN).
4. **Évaluation des performances** : Évaluation du modèle à l'aide de métriques telles que la précision, le rappel et la F1-score.
5. **Analyse des résultats** : Analyse des résultats obtenus, discussion sur l'efficacité du modèle et suggestions d'améliorations.

## Prérequis

Avant d'exécuter ce projet, vous devez installer les dépendances suivantes :

- Python 3.x
- Les bibliothèques suivantes :
  - `pandas` : pour le traitement des données
  - `numpy` : pour les calculs numériques
  - `matplotlib` : pour la visualisation des données
  - `scikit-learn` : pour l'entraînement des modèles de machine learning
  - `opencv` : pour le traitement des vidéos

Les versions spécifiques des bibliothèques sont listées dans le fichier `requirements.txt`.

## Installation

Clonez le projet et installez les dépendances en utilisant `pip` :

```bash
git clone https://github.com/votre-utilisateur/le_projet.git
cd le_projet
pip install -r requirements.txt

