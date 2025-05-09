---
title: Questionnaire Dynamique pour Dépannage
publishDate: 2025-04-12 00:00:00
img: /assets/Goweb.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |

tags:
  - FullStack
  - React
  - Node
  - Express
  - TypeScript
  - Tailwind CSS
---

#### Presentation : 

Dans le cadre d’un test technique pour l’entreprise Goweb, j'ai développé en quelques jours une application web permettant de qualifier un chantier de dépannage de manière dynamique.

L’utilisateur (le client) répond à une série de questions dont le parcours évolue en fonction de ses réponses. Une fois le questionnaire terminé, il accède à un récapitulatif et peut transmettre ses coordonnées pour être recontacté par un artisan.

Côté artisan, une interface d’administration permet de consulter l’ensemble des soumissions (réponses + informations de contact).

#### Spécifications techniques :

##### Frontend :

Développé avec React.js (TypeScript) et stylisé avec Tailwind CSS, le parcours utilisateur est dynamique : les questions s’enchaînent en fonction des réponses, avec la possibilité de revenir en arrière. Une fois le formulaire complété, un récapitulatif s’affiche avant la soumission des données. Le tout est 100% responsive, conforme aux maquettes Figma, et accompagné de tests unitaires (Vitest + React Testing Library) pour garantir la fiabilité des composants clés (formulaire, navigation...).

##### Backend :

Une API construite avec Node.js + Express.js permet de traiter et sauvegarder les soumissions. Les données sont stockées sous forme de fichier JSON pour la démonstration, avec validation et nettoyage des entrées utilisateur grâce à la librairie validator. La sécurité est renforcée par une clé API qui protège l’accès aux données des soumissions. Des tests automatisés (Jest + Supertest) assurent la robustesse des routes principales et des fonctions critiques (validation des champs, gestion des erreurs…).

##### 👉 lien github du projet : [DiagPro](https://github.com/yoniGdr/DiagPro)

##### 👉 [Mini démo](https://drive.google.com/file/d/1o_XlneRn7quD18-vXLbx06DlYD2qtvHF/view)