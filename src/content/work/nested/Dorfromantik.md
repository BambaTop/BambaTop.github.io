---
title: Dorfromantik
publishDate: 2024-10-27
img: /assets/dorfromantik.png
img_alt: Capture d'écran du projet Dorfromantik en action
description: |
  Développement d'un jeu inspiré de Dorfromantik, où le joueur assemble des tuiles hexagonales pour créer un paysage harmonieux.
tags:
  - Développement
  - Java
  - Jeu vidéo
  - MVC
---

### Présentation du projet

Dans le cadre de la **SAE 3.1**, nous avons développé un jeu inspiré de **Dorfromantik**, où le joueur doit assembler des tuiles hexagonales pour former un paysage cohérent.  

Le projet a été réalisé en collaboration avec **David Akagunduz et Vincent Teissier**.

### Fonctionnalités principales

- **Système de jeu** : Placement et rotation de tuiles hexagonales pour optimiser le score.
- **Mouvement de caméra** : Navigation fluide grâce à un contrôle intuitif.
- **Gestion du score** : Calcul basé sur les connexions de terrain similaires.
- **Interface minimaliste** : Un design simple favorisant une immersion agréable.
- **Classement des scores** : Affichage du top 10 des meilleurs résultats.

### Architecture et Algorithmes

Le projet est basé sur une **architecture MVC (Modèle-Vue-Contrôleur)** permettant une séparation claire entre la logique du jeu, l'affichage et les interactions utilisateur.

- **Modèle** : Gestion des tuiles (`Tile.java`), des terrains (`TerrainType.java`) et du score (`Pocket.java`).
- **Vue** : Interface utilisateur avec des classes dédiées (`GameView.java`, `MenuView.java`, etc.).
- **Contrôleur** : Gestion des interactions (`GameController.java`, `HexagonMouseListener.java`).

L'algorithme principal utilise une **recherche en profondeur (DFS)** pour détecter les zones connectées du même type de terrain et attribuer un score en conséquence.

### Technologies utilisées

- **Langage** : Java
- **Paradigme** : Programmation orientée objet (POO)
- **Frameworks** : Java Swing pour l'interface graphique
- **Architecture** : MVC

### Conclusion

Ce projet nous a permis d'approfondir nos compétences en **développement Java**, en gestion d’interface utilisateur et en **structuration de projet**. Nous avons également appris à mieux collaborer et organiser notre code pour faciliter l’évolution du projet.

[Consulter le dépôt Git du projet](https://github.com/bamba131/Dorfromantik)
