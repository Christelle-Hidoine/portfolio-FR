---
title: Task Management
publishDate: 2023-04-06 00:00:00
img: /assets/task-manager.png
img_alt: Liste de tâches sur fond noir/violet, avec une catégorie et des tags pour définir chaque tâche et un bouton "nouvelle tâche" pour ajouter une nouvelle tâche
description: |
  Une application de gestion de tâches personnelles et/ou professionnelles selon les besoins. Elle permet d'enregistrer des tâches, les modifier, les supprimer, ajouter une catégorie et/ou des tags pour les reconnaitre plus facilement.
tags:
  - Laravel
  - API REST
  - Single Page Application
---

## Conception d'une application de gestion de tâches

Le code est disponible sur <a href="https://github.com/Christelle-Hidoine/Task-Management">GitHub</a>.

Développement d'une application de gestion de tâches en créant une **API REST** et en utilisant le concept de **SPA** (Single Page Application).

### CRUD

Mise en place de toutes les méthodes permettant la gestion des données du site internet sous forme d'API REST : liste, création, mise à jour, suppression.

### Structure

Ce site a été conçu selon l'architecture MVC (model, view, controller) et utilise les namespaces.

Le framework LARAVEL est utilisé pour gérer les endpoints (route d'accès à l'API) et toute la manipulation de la base de données dans un dossier \backend.

Utilisation de Javascript pour la création de la partie frontend en format Single Page Application afin d'obtenir les meilleures performances de chargement de page et d'expérience utilisateur.

### Schéma relationnel

Relation ManyToMany dans l'utilisation des tags et OneToMany pour traiter les catégories.

Test de la récupération des données en format json.

### Responsive design

Ce site a été crée en Mobile First et possède également un visuel adapté pour le format tablet et desktop.
Utilisation des Media Queries dans la partie CSS.

### Technologies

Les technologies utilisées pour sa réalisation : PHP 7.4, Laravel 8, Javascript, HTML5, CSS3.
