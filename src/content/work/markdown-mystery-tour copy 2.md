---
title: Outil de supervision PAF
publishDate: 2020-03-02 00:00:00
img: /portfolio/assets/projectPAF/image_statistiques.png
img_alt: Page de statistiques de l'application
description: |
  Projet développé au cours de mon stage de fin d'année en master 2
tags:
  - Front End
  - Bootstrap
  - JavaScript
  - Python



---

## Objectif du projet

Le projet PAF (Portique Anti-Fraude) est un outil de supervision pour pouvoir surveiller quotidiennement les données renvoyées par les nouveaux PAF, équipements de sécurité mis en place dans la plupart des stations de métro de Marseille.


<br/>

## Fonctionnalités principales

Pour ce projet, je suis principalement intervenu côté front end

### Front end

L'interface a été développée pour être claire, responsive et agréable à utiliser. Les fonctionnalités incluent :

  - Page d'accueil interactive avec une liste déroulante pour sélectionner une station de métro
  - Affichage dynamique des données des portiques en fonction de la station sélectionnée
  - Navigation entre différents onglets
  - Sélection des périodes avec des champs pour la date de début et de fin
  - Graphiques dynamiques basés sur les sélections (station, portique, période), avec possibilité de zoom
  - Exportation des graphiques en formats JPEG et PNG
  - Gestion des erreurs et des données manquantes
  - Affichage clair et responsive des données brutes enregistrées en temps réel par les portiques
  - Visualisation de l'état des portiques en temps réel via des indicateurs colorés

### Back end

Les fonctionnalités du back end que j'ai pu développer :

  - Créations de quelques API permettant au front end de récupérer les données nécessaires à l'affichage

## Technologies utilisées 

  **Front end** : Javascript, Bootstrap

  **Back end** : MongoDB, Python

  **Autres** : CanvasJS

### Défis techniques rencontrés

  Un des défis majeurs a été que je devais m'auto-former sur une durée assez courte sur plusieurs technologies, telles que CanvasJS, Ajax tout en renforçant mes compétences en JavaScript.

#### Ce que j'ai appris

  - Utilisation de différentes technologies comme CanvasJS ou encore Ajax
  

## Galerie

  <img src="${import.meta.env.BASE_URL}/assets/projectPAF/image_statistiques2.png" alt="Image 1" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}/assets/projectPAF/image_error.png" alt="Image 2" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}/assets/projectPAF/image_donneebrutes.png" alt="Image 3" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}/assets/projectPAF/image_etats.png" alt="Image 4" class="rounded-lg shadow"/>
  <img src="${import.meta.env.BASE_URL}/assets/projectPAF/image_export.png" alt="Image 5" class="rounded-lg shadow"/>