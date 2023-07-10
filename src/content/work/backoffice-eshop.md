---
title: Backoffice eShop
publishDate: 2023-04-23 00:00:00
img: /assets/backoffice_eShop.png
img_alt: Page d'accueil du backoffice du site internet dans les Shoes avec 2 colonnes, liste des catégories et liste des produits
description: |
  Backoffice d'un site marchand Dans les Shoes avec permissions pour le traitement des données
tags:
  - PHP
  - Permissions
  - Sécurité
---

## Conception du backoffice d'un site internet

Le code est disponible sur <a href="https://github.com/Christelle-Hidoine/BackOffice-EShop">GitHub</a>.

Dans le cadre de mon apprentissage, j'ai développé le backoffice d'un site marchand en utilisant la méthode SCRUM Agile en 3 sprints pour le réaliser.

### CRUD

Mise en place de toutes les méthodes permettant la gestion des données du site internet : liste, création, mise à jour, suppression.

### Sécurité

La sécurité est au coeur de ce site internet.

Les routes sont accessibles selon les permissions accordées à l'aide d'un Access Control List (ACL) qui sera vérifié à chaque authentification.

Les tokens jouent également un rôle important dans l'envoi de données à notre base de données. Ils sont placés dans chaque formulaire et sur les liens de suppression des données afin de garantir l'utilisation la plus sécurisée de ce site et d'éviter le renvoi de formulaire une seconde fois (pour contrer les attaques CSRF)

Les données sont filtrées et traitées avant d'être transmises à notre base de données (pour contrer les attaques XSS).

### Structure

Ce site a été conçu selon l'architecture MVC (model, view, controller) et utilise les namespaces.

### Technologies

Les technologies utilisées pour sa réalisation : PHP 7.4, Bootstrap 5.1, HTML5, CSS3
