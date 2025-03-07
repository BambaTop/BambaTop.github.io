---
title: Bakefile
publishDate: 2025-01-19
img: /assets/bakefile.png
img_alt: Capture d'écran du projet Bakefile en action
description: |
  Développement d'un outil de gestion des dépendances similaire à Make, permettant d'automatiser la mise à jour de fichiers à l'aide d'un fichier de configuration spécifique : le Bakefile.
tags:
  - Développement
  - Java
  - Algorithme
  - Compilation
---

### Présentation du projet

Dans le cadre de la **SAE 31_2024**, nous avons développé **Bakefile**, un utilitaire inspiré de **Make**, permettant de gérer les dépendances entre fichiers et d’automatiser leur mise à jour.

Le projet a été réalisé en collaboration avec **Amir Kabbouri et Athiran Nagathurai** sous la supervision de **Luc Hernandez**.

### Fonctionnalités principales

- **Mise à jour des cibles** : Exécution conditionnelle des tâches en fonction des modifications des fichiers sources.
- **Gestion des dépendances** : Détection automatique des fichiers à recompiler.
- **Exécution des recettes** : Utilisation de `ProcessBuilder` pour lancer les commandes définies.
- **Débogage avancé** : Mode `-d` pour afficher des informations détaillées sur l'exécution.
- **Détection des cycles** : Vérification des dépendances circulaires pour éviter les boucles infinies.
- **Support des cibles `.PHONY`** : Permet d'exécuter des tâches sans dépendre de fichiers réels.

### Architecture et Algorithmes

Le projet repose sur une structure modulaire avec plusieurs classes interconnectées :

- **`BakeReader`** : Lecture et interprétation du fichier `Bakefile`.
- **`GrapheDep`** : Gestion des dépendances sous forme de graphe dirigé.
- **`BakeExecute`** : Exécution des commandes associées aux cibles.
- **`BakeComparator`** : Comparaison des dates de modification des fichiers pour déterminer la nécessité d'une mise à jour.

L’algorithme central repose sur un **parcours en profondeur (DFS)** pour détecter les cycles et établir un **ordre de compilation** optimal.

### Technologies utilisées

- **Langage** : Java
- **Structures de données** : HashMap, ArrayList, Graphes dirigés
- **Gestion du code** : Gitea

### Conclusion

Ce projet nous a permis de mieux comprendre le fonctionnement des outils de build, d’améliorer nos compétences en **gestion des dépendances**, et de renforcer notre approche de développement collaboratif.

[Consulter le dépôt Git du projet](https://grond.iut-fbleau.fr/kabbouri/SAE32_2024)
