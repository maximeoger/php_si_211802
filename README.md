# CRUD_php_si_2119802

## Description

MySPORT est un réseau social fictif permettant de mettre des sportifs amateurs et professionnels en relation. Il a été réalisé à HETIC dans le cadre d'une semaine intensive de php par Anthony Thuillez, Mathieu Blok, Joel Pokam, Yannis Kara et Maxime Oger afin de mettre en pratique une WEB app sur la base du CRUD (Create, Read, Update, Delete)

## fichiers



## Fonctionnalités

* Newsfeed.php -> affiche les entrées de type texte depuis la bdd dans le fil d'actualités
* add_user.php -> ajoute un utilisateur dans la bdd
* delete.php -> supprime une entrée du fil d'actualité
* edit.php -> modifie la valeur de la colone "content" de la table "post" de la bdd via son ID récupéré en POST

### schéma techniques



##Choix techniques

* Serveur -> Apache2.4
Le site est héberger en local via le serveur Apache2.
* Base de données -> MySQL 5.7
Les informations renseigné par l'utilisateur sont stockées dans la base de données.
* Langage -> Php 7.2
Le site est rendu dynamique, il execute les scripts afin de générer des documents HTML et de les renvoyer à l'utilisateur.
* extension PDO ->

##Comment ça marche?

Quand un script PHP est appelé, il passe par le serveur Web (ici Apache). Si l'extension du fichier correspond à ce que l'on a défini comme étant
l'extension PHP, le serveur demande à l'interpréteur PHP d'exécuter le code PHP contenu dans le fichier. L'exécution de ce code PHP entrainera
éventuellement un échange d'informations avec la base de données. Au final, c'est une page HTML (avec éventuellement du Javascript) qui est retourné
par le script PHP et renvoyé au serveur web (Apache). Le résultat est émis vers le navigateur. FIN du parcours.
