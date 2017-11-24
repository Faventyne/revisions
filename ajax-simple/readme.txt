Le but est de passer des formulaires existants en Ajax. S'il vous en reste dans le projet TOTO, transformez-les en Ajax en suivant le guide ci-dessous. Sinon, utiliser le fichier form.php fourni (qui n'aura pas d'insertion).
	
1) Etapes pour passer un formulaire existant en Ajax :
	* intercepter la soumission du formulaire
	* en JS, "serializer" les données du formulaire pour les envoyer en Ajax sur le fichier "ajax/country.php"
	* dans ce nouveau fichier, placer le traitement des données en POST et insérer ou modifier en DB (reprendre le code existant)
	* la réponse du fichier "ajax/country.php" sera l'id si tout a fonctionné, 0 sinon (utilisez la fonction die('0'); )
	* après la réponse du fichier "ajax/country.php", côté javascript, afficher une alerte pour informer l'utilisateur
	* puis, si dans le cas d'une insertion :
		** rediriger sur la même page avec le bon ID => ?id=42

---------
En option
---------
2) Faire de même avec le formulaire de City et Session
3) Faire de même avec le formulaire de Session