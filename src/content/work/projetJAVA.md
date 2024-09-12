---
title: Projet Java
publishDate: 2019-05-02 00:00:00
img: /assets/projetJava.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |

tags:
  - Java
  - Java Swing
  - POO
  - Travail en équipe
---

##### Presentation : 

Ce projet universitaire en équipe de 4 consiste en la modélisation et codage de deux jeux, cette modélisation permettra d'implanter différents jeux. Les jeux ont une base commune mais les règles, les types de personnages, la composition du terrain de jeu pourra varier. L’objectif est donc faire une modélisation qui permettera à un développeur de créer un nouveau jeu en se servant de ce qui est déjà réalisé ou en ajoutant modérément des classes pour s’adapter simplement aux spécificités de son jeu sans toucher au code des classes que nous avons codé.

En effet, il s'agit de deux versions de jeu à realiser : un jeu de guerre et un jeu de développement agricole.

Ces deux jeux sont constitué d'un plateau, de joueurs et de règles.

##### Rules :

Le plateau est de forme réctangulaire, celui-ci est divisé en tuiles, les joueurs manipulent donc des personnages qu'ils vont pouvoir positionner sur les tuiles, chaque tuile peut produire un type de ressources que récoltent les joueurs à chaque tour de jeu. Ces ressources peuvent être  converties.

Jeu de guerre :

dans ce jeu, le joueur déploie ses armées sur des territoires et nourrit ses soldats et surveille donc ses adversaires qui pourront lui voler des armées.

Ces armées sont caractérisées par un nombre de guerriers( entre 1 et 5) et possédent de l'or gagné lors des conquêtes de territoires. Elles prennent position sur des tuiles de type

    - Montagnes
    - Plaines
    - Désert
    - Forêt.

 Ces derniéres produisent respectivement :

    - Roche
    - Blé
    - Sable
    - Bois
 
Des tuiles de type océan existent également mais ne peuvent pas recevoir d'armée.
L'objectif du jeu est d'obtenir le plus de points aprés 10 tours.

Jeu de développement agricole : 

Dans ce jeu, le joueur déploie des ouvriers agricoles qui doivent être payés afin d'exploiter des territoires. Grâce à leur production, ces ouvriers gagnent de l'or.

Les tuiles et ressources sont les memes que pour le WarGame.

L'objectif du jeu est d'obtenir le plus de points aprés 10 tours. Les points sont calculé de la façon suivante: La somme total de l'or des ouvriers deployées.

#####  lien github du projet : [ProjetJava](https://github.com/yoniGdr/MazeGame).