# Notes pour la soutenance – Fabio VOLIANI

---

## Introduction

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

- Stack : WordPress Bedrock (sécurité, gestion des dépendances via Composer), Twig (séparation du code et du design), ACF Pro (flexibilité pour le client), Tailwind CSS (intégration rapide, responsive), PHP, Git.
- Outils de gestion :  
  - Furious : tickets internes, suivi des tâches, priorisation
  - Freshdesk : tickets clients, historique des demandes, suivi des incidents
  - Mattermost : communication quotidienne, partage de fichiers, canaux par projet
- Environnements de dev : Docker pour simuler la prod, XAMPP pour certains tests rapides.
- Importance de la maîtrise de ces outils pour garantir la qualité, la sécurité et la maintenabilité du projet.

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

---

## Questions ?

- Préparer des exemples concrets à donner si questions sur :  
  - Bloc « Sélection spectacles » (fonctionnement, avantages pour le client)
  - Gestion des tickets (organisation, priorisation)
  - Stack technique (pourquoi Bedrock, pourquoi Tailwind, avantages de Twig)
- Être prêt à expliquer comment j’ai géré les difficultés et ce que j’en ai retiré
