DOCUMENTATION SUR GIT
	Source : http://www.siteduzero.com/informatique/tutoriels/gerez-vos-codes-source-avec-git
	git status // voir le status des fichiers et dossiers

Cr�ation r�pertoire :
	git init
	git clone LIEN // Copie tout les fichiers et dossiers d'un lien git
	cd FICHIER_AJOUTER // Pour que les autres fonctions fonctionne

Ajout des fichiers modifier
	git add . // Ajoute tout les fichiers
	git add "fichier.txt" // Ajoute un fichier

Modification des fichiers
	git commit -am "Message du commit"
	git commit -a
		Faire i, �crire le message, faire :x

Publier les changements
	git push

Aller chercher les changements
	git pull

GESTION DES BRANCHES

	git branch // Affiche toute les branches (celle avec un * est elle o� on est actuellement)

Ajout branche
	git branch "nom_de_la_branche"

Supprimer branche
	git branch -d "nom_de_la_branche" // Supprime la branche en sassurent que tout les fichiers on �t� commit�
	git btanch -D "nom_de_la_branche" // Supprime la branche en sassurent de rien

Aller � une branche
	git checkout "nom_de_la_branche"

Fusion de branche
	Aller dans la branche qui recoit les modifications d'une autre branche
	git merge "nom_de_la_branche"