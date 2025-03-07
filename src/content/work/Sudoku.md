---
title: Sudoku Solver  
publishDate: 2024-05-16  
img: /assets/Sudoku.png  
img_alt: Capture d'écran du projet Sudoku en action  
description: |
  Développement d'une application de conception et de résolution de grilles de Sudoku, avec mode automatique et manuel.
tags:
  - Développement
  - Java
  - Jeu vidéo
  - Backtracking
---

### Présentation du projet

Dans le cadre de la **SAE 3.1**, nous avons développé une application permettant de **concevoir et résoudre des grilles de Sudoku**. L’utilisateur peut soit générer une grille et la remplir manuellement, soit laisser l’algorithme la résoudre automatiquement.

### Fonctionnalités principales

- **Génération de grilles** : Création aléatoire de grilles jouables.
- **Éditeur de grilles** : Possibilité de modifier une grille et de sauvegarder les configurations.
- **Mode manuel** : Résolution interactive avec vérification des erreurs.
- **Mode automatique** : Algorithme de backtracking pour résoudre les grilles instantanément.
- **Interface intuitive** : Développée avec Java Swing pour une navigation fluide.

### Architecture et Algorithmes

L’application repose sur une architecture modulaire favorisant la séparation des responsabilités :

- **Modèle** : Gestion des grilles et des règles du Sudoku (`GrilleSudoku.java`, `GenerateurGrille.java`).
- **Vue** : Interface graphique pour l’affichage et l’interaction (`ElaborationGrille.java`, `Resoudre.java`).
- **Contrôleur** : Gestion des entrées utilisateur et de la logique du jeu (`GestionFichier.java`, `Resolution.java`).

L’algorithme de résolution repose sur le **backtracking**, une méthode récursive permettant d’essayer différentes valeurs et de revenir en arrière en cas d’erreur.

### Technologies utilisées

- **Langage** : Java  
- **Paradigme** : Programmation orientée objet (POO)  
- **Frameworks** : Java Swing pour l’interface graphique  

### Conclusion

Ce projet m'a permis de renforcer mes compétences en **Java**, en **algorithmes de recherche** et en **développement d’interfaces utilisateur**. J'ai appris à organiser mon code efficacement et à gérer les erreurs pour améliorer l'expérience utilisateur.

[Consulter le dépôt Git du projet](https://github.com/bamba131/Sudoku)
