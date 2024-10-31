update: 29/07/2024 - correction d'erreurs due à un écran blanc, j'ai changer le nom de la bdd

<-- Table des matières -->
- /media -------> Racines des images du site
- /icon --------> Illustrations utilisé sur le site
- /articles ----> Vue des articles
- /backoffice --> Backoffice complet
- /images ------> Vue du carrousel
- /layout ------> Page d'accueil
- /main --------> Sélection des pages à afficher
- favicon.ico --> icone du site

<-- Informations utiles -->
- Le site à été au maximum codé à l'aide de bootstrap pour le responsive.

<-- Outils utilisés -->
- Bootstrap 5
- Jquery 3.6.0
- WAMP server
- phpMyAdmin 5.0.2
- https://undraw.co/illustrations (pour des illustrations libres de droits)

<-- Base de données -->

- le fichier sql de ma bdd se trouve dans MVC/bdd/monsite.sql
- la connexion à la bdd se fait depuis le fichier MVC/controllers/Login.php
- phpMyAdmin:
	login: root
	mdp:
	serveur: MySQL

<-- Backoffice -->
- Pour acceder au backoffice il faut cliquer sur le "©" du copyright du footer
- Portail:
	login: admin
	mdp: password (tooltip sur hover du bouton "Se connecter")
- si vous ajouter une image sans préciser de chemin, le chemin de l'image sera /media par défaut
