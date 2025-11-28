---
title: DATA Prédiction - Projet VVVA
publishDate: 2024-11-15 00:00:00
img: /assets/stock-1.jpg
img_alt: Dashboard de prédiction et analyse des résultats de Formule 1 avec visualisations interactives
description: |
  Un outil de prédiction des résultats de Formule 1 intégrant l'impact de la météo et proposant un simulateur interactif et un dashboard d'analyse.
tags:
  - Data Science
  - Intelligence Artificielle
  - Python
  - Machine Learning
  - Streamlit
  - Visualisation
---

# Projet VVVA – Prédiction et Analyse des Résultats de Formule 1

Le projet VVVA est une solution de data science et d'intelligence artificielle visant à prédire les résultats des courses de Formule 1 en s'appuyant sur des données historiques enrichies par des facteurs environnementaux, notamment la météo. L'objectif principal est de fournir un outil interactif et pédagogique permettant à la fois l'analyse statistique et la simulation prospective des Grand Prix.

## Objectifs du projet

Grâce à une intégration de données multi-sources (résultats passés, caractéristiques des circuits, performances des pilotes et écuries, conditions météorologiques), le projet met en place un pipeline complet comprenant :

- **Nettoyage et transformation des données** en format optimisé `.parquet` pour des traitements rapides
- **Exploration et visualisation avancée** des tendances : impact de la météo sur les écarts, taux d'abandon, avantages pour certaines équipes
- **Modélisation prédictive** via des algorithmes robustes (`RandomForestClassifier`) capables d'anticiper les classements futurs
- **Simulateur de Grand Prix interactif** : choix de l'année, des pilotes/écuries réels, génération de conditions météo aléatoires et prédiction dynamique des résultats
- **Dashboard intuitif (Streamlit)** permettant une expérience immersive avec comparaisons historiques, graphiques interactifs et scénarios "what-if"

## Fonctionnalités principales

### Pipeline de données
- Collecte et agrégation de données multi-sources
- Nettoyage et transformation en format `.parquet` pour des performances optimales
- Intégration de données météorologiques historiques

### Analyse et visualisation
- Exploration des tendances statistiques
- Visualisation de l'impact de la météo sur les performances
- Analyse des taux d'abandon par circuit et conditions
- Identification des avantages compétitifs des équipes

### Modélisation prédictive
- Utilisation de `RandomForestClassifier` pour la prédiction des classements
- Entraînement sur données historiques enrichies
- Évaluation et validation des modèles

### Simulateur interactif
- Sélection de l'année et des pilotes/écuries
- Génération aléatoire de conditions météorologiques
- Prédiction dynamique des résultats en temps réel
- Scénarios "what-if" pour explorer différents cas de figure

### Dashboard Streamlit
- Interface intuitive et immersive
- Graphiques interactifs et comparatifs
- Visualisation des tendances historiques
- Expérience utilisateur optimisée

## Points forts

Ce projet allie **précision statistique**, **visualisation claire** et **dimension ludique** grâce à la simulation, tout en intégrant une réflexion sur l'impact de facteurs exogènes comme la météo dans le sport automobile.

- Analyse approfondie des données de Formule 1
- Prédictions basées sur des algorithmes de machine learning
- Interface interactive et pédagogique
- Intégration de facteurs environnementaux complexes

