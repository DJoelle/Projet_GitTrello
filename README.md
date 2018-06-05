# Projet_GitTrello
Projet tutoriel sur la prise en main des technologies GITHUB TRELLO.

### Description du projet
Le projet est une simple application statique de gestion de profils (2 pages, login et dashboard).
L'utilisateur se connecte, a accès à son profil, et peut ajouter ou modifier des profils.

La page dashboard est constitué d'une section Bienvenue, une section Bouton Ajouter profil, une section profil utlisateur, une section liste des profils.

Une fois que l'on clique sur Ajouter profil, une fenêtre modale s'ouvre avec le formulaire d'ajout. Une fois le profil ajouté, une mise à jour de la liste de profil doit avoir lieu.

La liste de profil est un tableau avec le nom, le prenom le username du profil, la date de création et les boutons modifier et supprimer. Le bouton modiifer ouvre une fenêtre modale avec le profil sélectionné prêt à modiifer. La modification du profil en cours doit rafraichier la liste des profils. Le bouton supprimer supprime après confirmation le profil sélectionné.


### Instructions à suivre
Pour collaborer sur ce projet, les développeurs devraient respecter la nomenclature proposée par Git Flow, c'est à dire, celle qui propose de créer une branche pour chaques fonctionnalités (features).
On aura donc comme branches: 
- la branche develop (où toutes les fusions de nos features sont faites)
- la branche feature/initialisation (où la structure de notre projet est montée et les librairies et frameworks necessaires à notre production sont mises)
- la branche feature/login (où le template de la page connexion et la connexion elle même est gérée)
- la branche feature/dashboard (où le template dashboard et et toutes ses fonctionalités sont gérées)

Une fois que ces features sont tour à tour faites, on pourra fusionner ces features avec notre branche develop. On pourra faire avancer notre projet avec des versions et des corrections précises sur notre branche master