---
title: Great Place To Dev
publishDate: 2020-06-28 00:00:00
img: /assets/great-place-to-dev.png
img_alt: Une mappemonde avec des marqueurs sur les capitales de chaque pays concernés par le site internet et un filtre ouvert sur la partie gauche de la page avec des sélecteurs par critère
description: |
  Une application proposant un site comparatif des villes dans le monde pour travailler en remote avec une liste de critères correspondant aux préférences de celui qui fait la recherche
tags:
  - Recherche
  - Filtre
  - Javascript
---

## Projet de groupe avec la méthode SCRUM Agile

Ce projet a duré 1 mois et a eu pour but de nous faire travailler en groupe de 4 personnes à travers 4 sprints selon la méthode SCRUM Agile.

Le code est disponible sur <a href="https://github.com/Christelle-Hidoine/great-place-to-webdev">GitHub</a>.

<details><summary>Création d'un cahier des charges</summary>

- Définition d'un MVP (minimum viable product) avec les fonctionnalités essentielles
- Ajout des évolutions possibles une fois le MVP rempli
- Création des wireframes
- Etude de l'arborescence du site internet
- Choix des technologies utilisées
- Détermination des navigateurs compatibles
- Charte graphique et maquettage des principales pages du site
- Liste des routes Front et Back
- Création du dictionnaire de données, MCD et MLD
- Choix orientés sur l'accessibilité pour la charte graphique (couleurs, contrastes, taille des caractères, police d'écriture, les attributs HTML)
- Prise en compte du SEO
- Création d'un logo/slogan
- Choix du graphisme
- Détermination des permissions/rôles pour l'accès aux différentes pages du site
- Utilisation d'un Trello pour la création et le suivi des User Stories

</details>

### Création de la base de données

Prise en compte des schémas relationnels pour la création de la base de données selon le plan établi dans le cahier des charges

### Mise en place de la sécurité

Avec le framework Symfony, les routes sont sécurisés grâce aux ACL (access control list) et la hiérarchie des rôles est déterminée.

Les données récupérées sur les formulaires sont filtrées et validées avec les contraintes de validations définies dans les entity et lors de la création du formulaire.

Les templates laissent apparaitre uniquement les liens accessibles selon les rôles autorisés (ex : bouton d'accès aux favoris, lien d'accès au backoffice).

Les tokens sont implémentés automatiquement dans chaque formulaire et vérifiés à travers le UserAuthenticator.

### Structure

Le projet est organisé selon la méthode MVC.
Les templates sont séparés par catégorie et sont divisés en partials pour une meilleur maintenabilité du site.

### Performance

Nous utilisons des requêtes custom DQL (avec Doctrine) pour ne récupérer que les données nécessaires à chaque vue et améliorer les performances du site.

### Technologies

PHP 7.4, Symfony 5.4, Tailwind 3, CSS 3, HTML 5, Javascript, NoUiSliders, Leaflet, AmCharts, KNP Paginator
