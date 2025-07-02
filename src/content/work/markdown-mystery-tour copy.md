---
title: Project Management - Gestion de projets et de tâches
publishDate: 2025-04-01 00:00:00
img: /portfolio/assets/projectManagement/image_dashboard.png
img_alt: Page du dashboard de l'application
description: |
  Une application web de gestion de projet avec création de tâches, statuts personnalisés, utilisateurs et calendrier. 

tags:
  - Design
  - Full Stack
  - Angular
  - Spring Boot
  - Jikan API

---

## Objectif du projet

> Planifier. Suivre. Collaborer.

Project Management est une application web collaborative permettant à un utilisateur de gérer ses projets, d'organiser ses tâches selon leur statut (à faire, en cours, terminé, en retard), d'assigner des membres à chaque tâche et de visualiser les dates sur le calendrier.
Le projet a été développé dans le cadre d'un apprentissage pour améliorer mes compétences dans le développement full stack et la continuation dans l'apprentissage de Angular.


<br/>

## Fonctionnalités principales


### Front end

L'interface a été développée pour être claire, responsive et agréable à utiliser. Les fonctionnalités incluent :


  - Création d'un compte et connexion à l'aide d'un formulaire

  **Fonctionnalités disponibles après connexion :**
  - Ajout, modification ou suppression d'une tâche à l'aide d'un formulaire dynamique et responsive avec validation des champs
  - Visualisation de ses tâches de deux manières :
        - Sur un calendrier interactif (FullCalendar) 
        - Sur une page dédiée listant les tâches triées par statut
  - Association d'utilisateurs aux tâches
  - Attribution d'un statut pour chaque tâche via une liste prédéfinie (à faire, en cours, terminée)
  - Dashboard permettant de visualiser la situation de l'utilisateur par rapport aux tâches

### Back end

Le serveur Spring Boot assure :

  - Implémentation des entités Task, Project, User
  - Mise en place d'une API REST pour manipuler les entités du projet
  - La persistance des données via PostgreSQL
  - Contrôleurs REST pour exposer l'API
  - Authentification sécurisée avec JWT + refresh token


## Technologies utilisées 

  **Front end** : Angular 19, Tailwind CSS

  **Back end** : Spring Boot 3, Spring Security, JPA, PostgreSQL


## Architecture du projet

  Le projet suit une architecture en couches :
    - Controller
    - Service
    - Repository
    - Entity
  Cela permet une séparation claire des responsabilités de chaque couches et facilite la maintenance du code.


### Défis techniques rencontrés

  Un des défis majeurs a été de comprendre la relation parent-enfant entre les composants, car je ne comprenais pas comment les données pouvaient être transmises entre eux. Une autre difficulté a été l'intégration et l'utilisation des composants avancés, comme pour les calendriers qui ne fonctionnaient pas toujours.

#### Ce que j'ai appris

  - Compréhension de la relation parent-enfant entre différents composants Angular (@Output / @Input)
  - Utilisation de Tailwind CSS
  - Travail avec des composants avancés comme FullCalendar
  - Utilisation des dialogues Angular pour améliorer l'expérience utilisateur et une navigation fluide
  - Utilisation des DTO pour plus de clarté et de sécurité.




## Galerie


  <img src="${import.meta.env.BASE_URL}assets/projectManagement/image_taskDetails.png" alt="Image 1" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}assets/projectManagement/image_taskList1.png" alt="Image 2" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}assets/projectManagement/image_updateTask.png" alt="Image 3" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}assets/projectManagement/image_addTask.png" alt="Image 4" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}assets/projectManagement/image_calendar1.png" alt="Image 5" class="rounded-lg shadow"/>


