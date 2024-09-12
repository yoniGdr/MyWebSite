---
title: Serveur FTP
publishDate: 2023-02-14 00:00:00
img: /assets/ftpServ.webp
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |

tags:
  - Protocole FTP
  - Java
  - FileZilla
---

##### Presentation : 

Le logiciel est un serveur FTP basé sur la norme FTP.
Il permet aux utilisateurs de de télécharger des fichiers à partir d'un ordinateur hôte sur le réseau.
Les utilisateurs peuvent se connecter au serveur en utilisant un client comme FileZilla, et naviguer dans les répertoires de fichiers disponibles sur le serveur.  

Les concepts clés dans ce logiciel incluent la communication client-serveur, le protocole FTP et les sockets réseau.
Le logiciel utilise le protocole FTP pour gérer les communications entre le client et le serveur, et les sockets réseau pour gérer les connexions entre les deux.

Le logiciel gère les connexions entrantes en utilisant un socket d'écoute, et traite les commandes FTP envoyées par les clients en utilisant une analyse de chaîne pour identifier les commandes et exécuter les actions appropriées.
#####  lien github du projet : [Serveur FTP](https://github.com/yoniGdr/Serveur-FTP).