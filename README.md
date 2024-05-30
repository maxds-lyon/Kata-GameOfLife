# Kata du Game Of Life

## Pour commencer

Cliquez sur le bouton ci-dessous pour démarrer un nouvel environnement de développement :

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/maxds-lyon/Kata-GameOfLife.git)

Une fois que vous avez lancé l'environnement de développement, vous pouvez commencer à travailler sur le kata. Voici quelques commandes utiles que vous pourriez avoir besoin d'utiliser :

- Pour lancer l'application en local, utilisez la commande : `npm run dev`
- Pour lancer les tests, utilisez la commande : `npm run test`

Les dépendances nécessaires sont déjà installées dans l'environnement Gitpod.

Le code à modifier se trouve dans `src/game.ts` et les tests sont déjà présent dans `src/game.spec.ts`

# Introduction

Le Game of Life est un automate cellulaire imaginé par John Conway en 1970. Il s’agit d’un jeu de simulation sans joueur, où les cellules évoluent sur une grille en fonction de règles simples. Ce kata vous invite à explorer cet univers fascinant et à implémenter votre propre version du jeu.

# Règles du jeu

Le Game of Life se déroule sur une grille à deux dimensions, infinie théoriquement, mais limitée en pratique. Chaque cellule de cette grille peut être dans l'un des deux états suivants : vivante ou morte.

À chaque étape, l'état de chaque cellule pour le tour suivant est déterminé par les règles suivantes :

1. Une cellule morte avec exactement 3 cellules voisines vivantes devient une cellule vivante (naissance).
2. Une cellule vivante avec 2 ou 3 cellules voisines vivantes reste vivante (équilibre).
3. Dans tous les autres cas, une cellule vivante meurt ou reste morte (surpopulation ou isolement).

Notez que chaque cellule interagit avec ses huit voisines, qui sont les cellules directement adjacentes horizontalement, verticalement, ou diagonalement.

# Idées principales du kata

## 1. Les objectifs

- Comprendre les règles du Game of Life et les appliquer dans un programme
- Apprendre à manipuler des grilles et des coordonnées
- Développer des compétences en programmation orientée objet et en tests unitaires

## 2. L’approche standard

- Créer une classe `Cell` pour représenter une cellule et ses états (vivante ou morte)
- Créer une classe `Grid` pour gérer la grille et les interactions entre les cellules
- Implémenter les règles du jeu et les appliquer à chaque itération
- Utiliser des tests unitaires pour vérifier la validité de l’implémentation

## 3. Les avantages

- Améliorer sa logique de programmation en résolvant un problème complexe
- Découvrir un domaine passionnant de la simulation et de l’intelligence artificielle
- Se familiariser avec les automates cellulaires et leurs applications potentielles

## 4. Les erreurs des développeurs

- Ne pas respecter les règles du jeu ou les appliquer de manière incorrecte
- Manquer de modularité et de réutilisabilité dans le code
- Négliger les tests unitaires et la qualité du code

## 5. Les prérequis

### 5.1 Les prérequis techniques

- Connaissances en programmation orientée objet
- Maîtrise d’un langage de programmation (NodeJs, Java, etc.)
- Connaissance des tests unitaires

### 5.2 Les prérequis de compétences

- Capacité à lire et comprendre des règles complexes
- Aptitude à résoudre des problèmes et à décomposer un problème en sous-problèmes
- Patience et persévérance face à un défi de taille

# Conclusion

Le kata Game of Life est une excellente occasion de développer vos compétences en programmation tout en découvrant un domaine fascinant de la simulation et de l’intelligence artificielle. En suivant les règles du jeu et en appliquant une approche rigoureuse, vous pourrez créer votre propre version du jeu et explorer les nombreuses possibilités offertes par les automates cellulaires.
