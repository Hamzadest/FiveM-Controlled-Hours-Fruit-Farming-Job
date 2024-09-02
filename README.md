# FiveM-Controlled-Hours-Fruit-Farming-Job

Ce script pour FiveM introduit un job interactif de cueillette de fruits avec plusieurs étapes, des animations réalistes et une limitation du temps de travail pour équilibrer l'économie du serveur. Le joueur doit récolter des fruits, les transformer en jus, puis livrer les produits transformés pour gagner de l'argent.

# Description
Ce script pour FiveM introduit un job interactif de cueillette de fruits avec plusieurs étapes, des animations réalistes et une limitation du temps de travail pour équilibrer l'économie du serveur. Le joueur doit récolter des fruits, les transformer en jus, puis livrer les produits transformés pour gagner de l'argent.

# Fonctionnalités :

Récolte de fruits : Les joueurs peuvent récolter des pommes et des oranges à divers points de cueillette dispersés sur la carte. Une animation est jouée pour chaque action de récolte.
Limitation du temps de travail : Le temps de travail est limité pour éviter que les joueurs ne passent trop de temps à exploiter ce job, équilibrant ainsi le gameplay.
Transformation des fruits : Après la récolte, les joueurs doivent se rendre à un point de transformation où ils peuvent transformer les fruits en jus. Cette étape ajoute du réalisme et prolonge la durée du job.
Livraison des produits : Une fois les jus prêts, les joueurs doivent les livrer à un point de livraison pour recevoir leur paiement. Une animation de déchargement est également incluse.
Synchronisation multijoueur : Tous les joueurs sur le serveur voient les mêmes ressources et points de récolte.
Configuration
Le script est facilement configurable via le fichier config.lua, où vous pouvez ajuster :

Les points de cueillette (Config.FarmLocations)
Le point de transformation (Config.ProcessingLocation)
Le point de livraison (Config.DeliveryLocation)
La quantité de fruits récoltés par action
Le temps de travail maximal autorisé (Config.FarmLimit)

# Installation

Clonez le dépôt ou téléchargez le ZIP.
Décompressez et placez le dossier dans le répertoire resources de votre serveur FiveM.
Ajoutez ensure FiveMJobScript à votre fichier server.cfg.
Redémarrez votre serveur.

# Requis
ESX framework pour la gestion des inventaires et de l'économie.

# Crédits
Script développé par Hamza
