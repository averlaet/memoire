Liste des scripts et fichiers nécessaires à l'utilisation du chatbot XXXX

	- Méthode principale : main.pl

	- Modules:
		- gestion_profils.pm   : gère les profils
		- telegram_messages.pm : gère l'envoi et la réception des messages
		- process_response.pm  : évaluation des réponses et calcul de EF et I
		- selection_exercices.pm   : sélectionne les exercices pour des mots donnés 
		- selection_vocabulaire.pm : sélectionne le vocabulaire à revoir 
		
		
	- Fichiers: 
		- dossier_rappels.json : utilisé et modifié par gestion_profils 
		- exercices_total.csv  : fichier csv contenant tous les exercices 
		- exercices_total.json : fichier json utilisé par selection_exercices
		- 420245532.json : exemple d'un fichier utilisateur type
		- voc_total.csv  : fichier csv contenant le vocabulaire et les informations lexicales
		- voc_total.json : fichier json utilisé pour la sélection du vocabulaire et la récupération des informations lexicales
		- encoder_exercices.pl   : script qui encode les données des exercices dans un fichier json
		- encoder_vocabulaire.pl : script qui encode les données de vocabulaire dans un fichier json
	
	- Dossier images_exercices : contient toutes les image utilisées pour les exercices en format jpg. Ce dossier doit être placé dans dans la directory Telegram.
	  (C:\Strawberry\perl\site\lib\WWW\Telegram\)
