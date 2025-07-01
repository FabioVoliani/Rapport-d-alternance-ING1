# Notes pour la soutenance – Fabio VOLIANI


# PREPARATION

SITE EN LOCAL

Préparer une image, 

- PAGES
  - back-office = liste de tous les spectacles (lien = )
  - back-office = groupe de champs ACF "Sélection spectacles" 
  - back-office = options de l'accueil

- FICHIERS VSCODE
  - bloc selection-spectacles.twig
  - home.twig (montrer vite fait)


---

## Introduction

- *Phrase d'accroche* :  
  "Bonjour à toutes et à tous, merci d’être présents. Je vais vous présenter le bilan de mon année d’alternance chez Vernalis Interactive, et en quoi c'est une expérience qui m’a permis de découvrir et d’approfondir le métier de développeur web."
- Présenter mon parcours : arrivé chez Vernalis sans expérience en développement web, formation sur le tas.
- Motivation : envie de comprendre le web, de participer à des projets concrets, d’apprendre en équipe.
- Alternance : immersion dans le monde professionnel, découverte des attentes et des méthodes de travail.
- Objectifs fixés : devenir autonome sur des projets, maîtriser l’intégration web, apprendre à gérer des missions variées, développer la communication.

---

## Présentation de l'entreprise

- Vernalis Interactive : PME marseillaise, forte expérience dans le secteur public.
- Petite équipe : permet d’être polyvalent, d’avoir des responsabilités rapidement.
- Projets : sites pour mairies, communautés de communes, établissements publics, mais aussi quelques clients privés (American Vintage, Sophim…).
- Travail en synergie avec Quai 13 (autre agence dans les mêmes locaux).
- Importance de la proximité client : beaucoup d’échanges directs, adaptation rapide aux besoins.
- Valeurs : rigueur, adaptabilité, sécurité, accompagnement sur le long terme.

---

## Projet approfondi : Refonte du site de la salle de spectacle l'Étoile Châteaurenard

- Projet choisi car il est un projet complet de refonte de site internet mais aussi parce que c'était mon tout premier, et que c'est de ce fait une occasion singulière de le présenter.
- Contexte : site vieillissant, besoin de modernité, d’autonomie pour l’équipe de la salle.
- Objectifs :  
  - Refonte graphique (nouvelle charte, maquettes Figma)
  - Ajout de fonctionnalités : catalogue, agenda, sélection de spectacles à la une
  - Faciliter la gestion du contenu (éviter les interventions techniques pour chaque mise à jour)
- Mon rôle :  
  - Intégration des maquettes (HTML/CSS/Twig)
  - Développement de blocs Gutenberg personnalisés (ex : « Sélection spectacles »)
  - Mise en place de l’environnement local, gestion du déploiement
  - Suivi des tickets, échanges avec la cheffe de projet et le client

---

## Contexte technique

- **WordPress Bedrock** : structure avancée pour WordPress, gérée avec Composer.  
  Permet de séparer le cœur WordPress, les plugins et les thèmes pour une meilleure organisation, sécurité et gestion des dépendances.  
  Facilite la maintenance et le déploiement sur différents environnements.
- **Twig** : moteur de templates moderne pour PHP.  
  Sert à séparer la logique métier du code HTML, ce qui rend le code plus propre, réutilisable et facile à maintenir.  
  Permet de créer des vues dynamiques et modulaires.
- **PHP** : langage de programmation côté serveur.  
  Utilisé pour développer la logique des sites WordPress, les fonctionnalités personnalisées, et l’intégration avec la base de données.
- **HTML/SCSS** :  
  - HTML structure les pages web (titres, paragraphes, images, liens, etc.).  
  - SCSS (Sass) est un préprocesseur CSS : il permet d’écrire du code plus structuré et maintenable grâce aux variables, fonctions, imbrications, mixins, etc.  
  - Le SCSS est compilé en CSS classique pour être compris par le navigateur.
- **JavaScript** : langage de programmation côté client.  
  Permet de rendre les pages interactives (animations, formulaires dynamiques, filtres, sliders…).
- **Advanced Custom Fields Pro (ACF Pro)** : extension WordPress pour créer des champs personnalisés dans le back-office.  
  Permet de gérer facilement des contenus complexes, de créer des blocs Gutenberg sur mesure, et de donner plus d’autonomie au client pour la gestion du site.

- **Outils de gestion** :  
  - Furious : gestion des tickets internes, suivi des tâches, priorisation.
  - Freshdesk : gestion des tickets clients, suivi des incidents, historique des demandes.
  - Mattermost : messagerie d’équipe, partage de fichiers, canaux par projet.
- **Environnements de développement** :  
  - Docker : simule l’environnement de production, facilite la compatibilité et l’isolation des projets.
  - XAMPP : utilisé pour certains tests rapides en local.

- **Importance** :  
  - Maîtriser ces outils et technologies est essentiel pour garantir la qualité, la sécurité, la maintenabilité et l’évolutivité des projets réalisés chez Vernalis.

---

## Démarche et étapes du projet

- Analyse des besoins : réunions avec la cheffe de projet, la designer, échanges avec le client pour comprendre les attentes (ex : gestion autonome des spectacles, affichage dynamique).
- Maquettes Figma : adaptation pour le web, découpage des assets, vérification de la cohérence graphique.
- Installation locale : configuration Docker (versions PHP, MySQL), installation de Bedrock, gestion des dépendances.
- Intégration :  
  - Utilisation de Twig pour séparer la logique de l’affichage
  - Intégration responsive (mobile, tablette, desktop)
  - Respect de l’accessibilité (contrastes, navigation clavier)
- Création de blocs personnalisés :  
  - Bloc « Sélection spectacles » : permet au client de choisir les spectacles à mettre en avant, simple à utiliser dans le back-office
  - Autres blocs : slider, agenda, galeries, formulaires
- Tests :  
  - Multi-navigateurs (Chrome, Firefox, Edge, Safari)
  - Tests sur différents devices (simulateurs, mobiles réels)
  - Vérification des performances (poids des images, chargement)
- Mise en ligne : déploiement sur serveur de pré-production, retours du client, ajustements rapides grâce à la gestion des tickets.

---

## Illustrations et exemples

- Bloc « Sélection spectacles » :  
  - Présenter une capture du back-office (Annexe 10) : interface simple, choix des spectacles par glisser-déposer
  - Présenter le rendu sur le site (Annexe 9) : affiches dynamiques, liens vers les fiches spectacles
- Slider d’accueil :  
  - Gestion des images via ACF, possibilité de modifier l’ordre facilement
- Catalogue des spectacles :  
  - Filtres par catégorie, affichage responsive, adaptation mobile/desktop (Annexes 16-17)
- Autonomie client :  
  - Grâce à ACF, le client peut modifier textes, images, affiches sans intervention technique
  - Formation rapide du client à l’utilisation du back-office

---

## Difficultés rencontrées

- Compilation d’assets :  
  - Problèmes avec npm, Tailwind (versions, dépendances)
  - Solutions : documentation, nettoyage des modules, adaptation des fichiers de config
- Migration PHP/WordPress :  
  - Incompatibilités lors des upgrades, nécessité de tester chaque étape
  - Solutions : tests progressifs, sauvegardes régulières, échanges avec l’équipe
- Gestion des tickets :  
  - Beaucoup de demandes en parallèle, nécessité de prioriser
  - Solutions : utilisation rigoureuse de Furious/Freshdesk, communication claire avec le client et l’équipe
- Importance de la documentation :  
  - Pour garder une trace des solutions, faciliter la maintenance et la transmission

---

## Compétences mobilisées

- Techniques :  
  - Intégration web avancée (HTML, CSS, Twig, Tailwind)
  - Développement WordPress (Bedrock, ACF, blocs Gutenberg)
  - Utilisation d’outils de ticketing, gestion de versions avec Git
- Organisationnelles :  
  - Planification, gestion des priorités, suivi des tâches
  - Documentation des solutions, transmission à l’équipe
- Comportementales :  
  - Travail en équipe, communication régulière avec le client
  - Autonomie, capacité à apprendre rapidement, gestion du stress lors des pics d’activité

---

## Résultats et impact

- Site livré dans les délais, conforme à la charte graphique et aux attentes fonctionnelles
- Client satisfait, autonome pour la gestion des spectacles et du contenu
- Documentation claire : facilite la maintenance et l’évolution du site
- Valorisation du travail auprès de l’équipe, confiance accrue pour les projets suivants
- Expérience transférable sur d’autres projets similaires (ex : autres sites de collectivités)

---

## Analyse critique

- Points forts :  
  - Diversité des missions, montée en compétences rapide
  - Esprit d’équipe, entraide, accompagnement des collègues
  - Capacité à prendre du recul, à documenter et à transmettre
- Axes d’amélioration :  
  - Approfondir Docker, automatisation des tâches, sécurité web
  - Structurer davantage la documentation technique (ex : guides internes)
  - Développer une communication client plus proactive (anticiper les besoins, proposer des améliorations)
- Prise de recul :  
  - Importance de la polyvalence, de la rigueur, de la documentation pour la réussite des projets

---

## Conclusion et perspectives

- Année très formatrice, progression rapide et concrète
- Envie de continuer dans le développement web, viser plus de responsabilités (lead dev, gestion de projet)
- Objectif : approfondir l’expertise technique, continuer à apprendre et à transmettre à l’équipe
- Volonté de rester dans un environnement stimulant, avec des projets variés et une équipe soudée

**Points à développer à l’oral :**
- Cette alternance m’a permis de passer d’un niveau débutant à un niveau où je peux gérer un projet web de bout en bout, de l’intégration à la mise en production.
- J’ai pris confiance en mes capacités techniques : aujourd’hui, je sais installer, configurer, migrer, maintenir et faire évoluer un site WordPress complexe.
- J’ai aussi progressé sur le plan organisationnel : gestion des priorités, planification, documentation, communication avec l’équipe et les clients.
- Sur le plan humain, j’ai découvert l’importance de l’entraide, de la transmission des connaissances et de la prise d’initiative.
- Cette expérience m’a donné envie de continuer à progresser, à me spécialiser sur des aspects techniques avancés (automatisation, sécurité, devops, pipelines CI/CD), mais aussi à encadrer ou former d’autres alternants à l’avenir.
- Je souhaite également renforcer mes compétences en gestion de projet, pour pouvoir piloter des projets plus complexes et accompagner les clients dans la durée.
- Enfin, je retiens que la curiosité, la rigueur et la capacité à s’adapter sont essentielles pour évoluer dans le numérique : je veux continuer à cultiver ces qualités dans la suite de mon parcours.

---

## Questions ?

- Préparer des exemples concrets à donner si questions sur :  
  - Bloc « Sélection spectacles » (fonctionnement, avantages pour le client)
  - Gestion des tickets (organisation, priorisation)
  - Stack technique (pourquoi Bedrock, pourquoi Tailwind, avantages de Twig)
- Être prêt à expliquer comment j’ai géré les difficultés et ce que j’en ai retiré
