---
layout: post
title: Projet - Gestion de films (version dynamique)
---

## Exigences métier

L'objectif de ce projet est de créer une application de gestion de films. Les exigences techniques sont les mêmes que celle de la [version statique de l'application](mymovies-static), avec les exigences supplémentaires suivantes : 

* Les données de l'application sont stockées dans une base de données.
* Le clic sur le titre d'un film permet d'accéder à ses informations.

## Exigences techniques

Les exigences techniques sont les mêmes que celle de la [version statique](mymovies-static), avec les exigences supplémentaires suivantes :

* L'application est développée à l'aide du langage PHP.
* La base de données est hébergée par MySQL.
* L'accès à la base de données utilise l'API [PDO](http://php.net/manual/fr/intro.pdo.php).
* Les scripts permettant de créer la base de données et d'insérer des données de test sont stockées dans le répertoire `db/`.
* La duplication de code dans les pages PHP est **interdite**. Les portions communes (accès à la base de données, barre de navigation, pied de page, etc) sont regroupées dans un répertoire `includes/` et inclus partout où c'est nécessaire.

## Bonus

Le projet peut être enrichi avec les fonctionnalités métier suivantes :

* Ajout d'un nouveau film.
* Edition d'un film existant.
* Suppression d'un film après confirmation.
* Gestion des utilisateurs (inscription, connexion, déconnexion).
* Gestion de catégories.
* Possibilité de noter les films (système d'étoiles).
* ...

Du point de vue technique, on peut envisager d'utiliser un framework plutôt que du code PHP standard pour réaliser le projet.

## Exemple de résultat

Un exemple d'application est [disponible en ligne](https://mymovies-correction.herokuapp.com/index.php).

## Remise des projets

Les projets sont déposés via GitHub dans le même dépôt que la version statique.

