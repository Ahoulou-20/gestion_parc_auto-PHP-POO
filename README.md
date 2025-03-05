# gestion_parc_auto-PHP-POO
## Gestion de Parc Automobile

# Description du projet

Ce projet est une application de gestion de parc automobile permettant aux utilisateurs d'ajouter, consulter et louer des véhicules. Il est développé en PHP et suit une architecture orientée objet.

Fonctionnalités principales

Ajout de nouveaux véhicules (voitures, motos, camions)

Gestion des utilisateurs

Enregistrement des locations

Journalisation des actions

Calcul des tarifs de location

Structure du projet

Le projet suit une architecture modulaire avec les fichiers suivants :

# 📂 classes/

Vehicule.php : Classe de base pour les véhicules

Voiture.php : Classe héritée pour les voitures

Moto.php : Classe héritée pour les motos

Camion.php : Classe héritée pour les camions

TypeVehicule.php : Enumération des types de véhicules

Louable.php : Interface pour les objets louables

Utilisateur.php : Gestion des utilisateurs

Journalisation.php : Enregistrement des actions

GenerateurVehicules.php : Génération aléatoire de véhicules

# 📂 autoload.php

Fichier permettant le chargement automatique des classes PHP.

# 📂 index.php

Point d'entrée de l'application qui instancie les utilisateurs et génère des véhicules.

# Installation et exécution

# Cloner le projet :

# git clone https://github.com/Ahoulou-20/gestion_parc_auto-PHP-POO.git

# Lancer un serveur local (ex: avec WAMP, XAMPP ou un serveur PHP intégré) :

php -S localhost:8000

# Accéder à l'application via http://localhost:8000/gestion_parc_auto/index.php

# Technologies utilisées

# PHP (POO)

HTML/CSS/JavaScript (interface utilisateur)-pour la version web que je déploierai plus tard.

#Serveur local (WAMP, XAMPP)

Auteur

# Ahoulou Adouko Loïc Ivan

Licence

# Ce projet est sous licence MIT - Li@TrX .

