# Cahier des charges (Version propre & officielle)

# 1 Contexte du projet

Dans le cadre de la formation Jobintech, ce projet fil rouge a pour objectif de mettre en pratique l’ensemble des compétences acquises durant la formation, notamment en développement d’applications mobiles, backend Node.js, bases de données SQL et architecture logicielle.

Le projet consiste à développer une application mobile appelée Dojafi, destinée à aider les utilisateurs à gérer efficacement leurs traitements médicaux grâce à un système de rappels automatisés.

# 2 Problématique

L’oubli de la prise de médicaments est un problème fréquent pouvant entraîner :

Une baisse de l’efficacité des traitements

Des complications médicales

Une mauvaise observance thérapeutique

Il est donc nécessaire de proposer une solution numérique simple, fiable et accessible permettant aux utilisateurs de recevoir des rappels précis et personnalisés.

# 3 Objectifs du projet
- Objectif principal

Développer une application mobile sécurisée permettant aux utilisateurs de planifier, recevoir et suivre les rappels de prise de médicaments.

- Objectifs secondaires

Centraliser la gestion des médicaments

Automatiser les notifications

Offrir une interface intuitive

Garantir la sécurité des données utilisateurs

Mettre en œuvre une architecture backend professionnelle

# 4 Périmètre du projet
✅ Fonctionnalités incluses

Inscription et authentification des utilisateurs

Gestion du profil utilisateur

Ajout, modification et suppression des médicaments

Programmation des horaires de prise

Envoi de notifications push

Suivi des prises quotidiennes

Historique des rappels

❌ Hors périmètre

Paiement en ligne

Consultation médicale

Intégration avec des pharmacies

Gestion de dossiers médicaux complets

# 5 Utilisateurs cibles

Patients sous traitement médical

Personnes âgées

Personnes atteintes de maladies chroniques

Toute personne souhaitant mieux organiser ses prises de médicaments

# 6 Architecture générale
🔹 Frontend

Application mobile développée avec React Native + Expo

Navigation avec Expo Router

Gestion de l’état global avec Zustand

Stockage sécurisé avec Expo SecureStore

🔹 Backend

API REST développée avec Node.js + Express

Architecture MVC

Authentification avec JWT

Validation des données

Sécurisation des routes

🔹 Base de données

Base SQL (PostgreSQL)

ORM : Sequelize

Schéma normalisé (3NF)

Relations entre entités

# 7 Exigences fonctionnelles

L’utilisateur peut créer un compte

L’utilisateur peut se connecter et se déconnecter

L’utilisateur peut gérer ses médicaments

L’utilisateur reçoit des notifications automatiques

L’utilisateur peut consulter ses rappels quotidiens

Les données sont sécurisées

# 8 Exigences non fonctionnelles

Application performante et fluide

Interface simple et ergonomique

Sécurité des données

Compatibilité Android / iOS

Respect des bonnes pratiques de développement

# 9 Contraintes techniques

React Native + Expo

Node.js / Express

PostgreSQL

JWT + bcrypt

Docker pour le backend

API documentée (Swagger)

# 10 Livrables

Cahier des charges

Diagrammes UML

Base de données SQL

Backend API

Application mobile fonctionnelle

Documentation technique

Présentation finale