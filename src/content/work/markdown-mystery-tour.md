---
title: AnimeHub - Suivi d'animes en ligne
publishDate: 2025-01-010 00:00:00
img: /portfolio/assets/projectPAF/image_statistiques.png
img_alt: Image de la page d'accueil de l'application
description: |
  Un projet full-stack pour explorer, rechercher et gérer ses animes préférés grâce à l'API Jikan.
tags:
  - Design
  - Full Stack
  - Angular
  - Spring Boot
  - Jikan API
---

## Objectif du projet

> Watch what you love, track what you watch.

AnimeHub est une application web permettant à un utilisateur de rechercher des animés, de consulter leurs fiches détaillées et de les
ajouter à ses favoris.
Le projet a été développé dans le cadre d'un apprentissage en full-stack, de l'intégration d'une API externe dans le projet. Il m'a également permis de découvrir et d'apprendre un nouveau langage côté front end : **Angular**.

<br/>

## Fonctionnalités principales

### Front end

L'interface a été développé pour être claire, responsive et agréable à utiliser. Les fonctionnalités incluent :

- Création d'un compte et connexion à l'aide d'un formulaire
- Rechercher des animes via une barre de recherche
- Affichage des animes récupérés à l'aide de l'API externe sous formes de cards
- Pagination pour naviguer entre les pages de résultats
- Section "Recommandations" affichant les animes recommandés récupérés depuis l'API externe
- Section "Top Animes" affichant les top animes récupérés depuis l'API externe

**Fonctionnalités disponibles après connexion :**

- Ajout et supression d'un anime pour la liste des favoris
- Consulter ses animes favoris

### Back end

Le serveur Spring Boot assure :

- Mise en place d'une API REST pour manipuler les entités utilisateurs et favoris
- Authentification sécurisée avec JWT + refresh token
- La persistance des données (favoris et utilisateurs) avec PostgreSQL
- Contrôleurs REST pour exposer l'API
- Mapping des données récupérées depuis l'API externe

## Technologies utilisées

**Front end** : Angular 19, Bootstrap

**Back end** : Spring Boot 3, Spring Security, JPA, PostgreSQL

**Autres** : API externe "Jikan"

## Architecture du projet

Le projet suit une architecture en couches : - Controller - Service - Repository - Entity
Cela Permet une séparation claire des responsabilités de chaque couches et facilite la maintenace du code.

### Défis techniques rencontrés

Un des défis majeurs a été le développement d'une authentification complète et sécurisée à l'aide du JWT en Spring Boot. Un autre défi rencontré a été de comprendre le fonctionnement de l'interaction entre le front end et l'API externe, ainsi que l'adaptation des données reçues pour les transmettre correctement au back end. Un autre défis a été la création de l'authentification à l'aide de JWT en utilisant le refresh token.

#### Ce que j'ai appris

- Intégration et Utilisation d'une API externe dans un projet
- Implémenter une authentification sécurisée complète à l'aide du JWT en Spring Boot
- Utilisation de Angular

## Lien du projet

- https://github.com/YellowIceEtu/animeHub-app.git

## Galerie

  <img src="/portfolio/assets/images-AnimeProject/image_homePage2.png" alt="Image 1" class="rounded-lg shadow"/>
  <img src='/portfolio/assets/images-AnimeProject/image_homePage3.png' alt="Image 2" class="rounded-lg shadow"/>
  <img src="/portfolio/assets/images-AnimeProject/image_animeDetails1bis.png" alt="Image 3" class="rounded-lg shadow"/>
  <img src="/portfolio/assets/images-AnimeProject/image_animeDetails2.png" alt="Image 4" class="rounded-lg shadow"/>
