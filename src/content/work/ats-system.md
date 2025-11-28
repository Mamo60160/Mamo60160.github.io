---
title: Système ATS - Tri Automatisé des Candidatures
publishDate: 2024-10-20 00:00:00
img: /assets/stock-3.jpg
img_alt: Interface du système ATS avec tableau de bord de gestion des candidatures et filtres intelligents
description: |
  Un outil de tri et suivi des candidatures automatisé, permettant d'analyser, filtrer et gérer les CVs via une interface simple et rapide pour les recruteurs.
tags:
  - Python
  - Streamlit
  - Automatisation
  - Recrutement
  - Data Analysis
  - Interface Utilisateur
---

# Projet ATS – Système de Suivi et de Tri Automatisé des Candidatures

Le projet ATS (Applicant Tracking System) est une plateforme innovante conçue pour simplifier et accélérer le processus de recrutement. Développé en Python avec Streamlit, cet outil permet d'automatiser l'analyse des CVs, d'effectuer un tri intelligent et d'offrir une interface intuitive pensée pour les recruteurs.

## Objectif principal

Fournir une solution rapide, efficace et évolutive pour aider les services RH à gagner du temps et améliorer la qualité des recrutements grâce à une gestion centralisée et automatisée des candidatures.

## Fonctionnalités clés

### Analyse automatique des CVs
- **Détection automatique des compétences** : extraction et identification des compétences techniques et professionnelles
- **Analyse du niveau d'anglais** : évaluation automatique des compétences linguistiques
- **Détection de la localisation** : identification géographique pour faciliter le tri géographique

### Filtres dynamiques et scoring personnalisé
- **Filtres avancés** : recherche par compétences, localisation, niveau d'anglais, et autres critères personnalisés
- **Scoring intelligent** : priorisation automatique des profils en fonction des critères définis par le recruteur
- **Tri personnalisable** : organisation des candidatures selon les besoins spécifiques

### Gestion des statuts
- **Statuts personnalisables** :
  - ✅ **Sélectionné** : candidats retenus pour la suite du processus
  - 🕐 **En attente** : candidatures en cours d'évaluation
  - ❌ **Rejeté** : profils non retenus
- **Mise à jour individuelle ou en masse** : gestion flexible des statuts pour optimiser le workflow

### Export intelligent
- **Export CSV** : génération de fichiers pour les profils sélectionnés ou en attente
- **Export ZIP** : regroupement automatique des CVs rejetés dans une archive
- **Format structuré** : données prêtes pour l'import dans d'autres systèmes

### Restauration et suivi RH
- **Restauration de CVs** : possibilité de restaurer des candidatures précédemment rejetées
- **Page de résumé** : tableau de bord présentant les statistiques globales
  - Compteurs par statut
  - Top villes des candidats
  - Distribution des scores
  - Métriques de performance

### Expérience utilisateur optimisée
- **Conservation des statuts** : les statuts sont conservés même après filtrage
- **Mise à jour instantanée** : modifications en temps réel sans rechargement de page
- **Interface intuitive** : design épuré et fonctionnel adapté aux recruteurs

## Points forts du projet

### Gain de temps considérable
- Automatisation des tâches répétitives d'analyse et de tri
- Réduction du temps de traitement des candidatures de plusieurs heures à quelques minutes

### Réduction des erreurs
- Élimination des erreurs manuelles grâce à l'automatisation
- Traitement cohérent et standardisé de toutes les candidatures

### Accessibilité
- Interface simple mais puissante, adaptée aussi bien aux petites structures qu'aux grandes entreprises
- Pas de formation technique requise pour utiliser l'outil

### Évolutivité
- Architecture modulaire permettant l'ajout de nouvelles fonctionnalités
- Possibilités futures d'intégration :
  - Matching par intelligence artificielle
  - Envois automatiques d'emails aux candidats
  - Intégration avec des plateformes de recrutement externes
  - Analyse prédictive des meilleurs profils

## Technologies utilisées

- **Python** : langage principal pour le traitement des données et la logique métier
- **Streamlit** : framework pour créer l'interface utilisateur web interactive
- **Traitement de documents** : analyse et extraction d'informations depuis les CVs
- **Data processing** : manipulation et structuration des données candidats

## Impact

Ce système transforme le processus de recrutement en le rendant plus efficace, plus rapide et plus précis. Il permet aux recruteurs de se concentrer sur l'essentiel : l'évaluation qualitative des candidats plutôt que sur les tâches administratives répétitives.

