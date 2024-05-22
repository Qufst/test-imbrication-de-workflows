# test-imbrication-de-workflows

# Objectif 

L'objectif de ce dépôt est de trouver une méthode pour centraliser dans un dépôt le lancement de plusieurs autres dépôts et de récupérer des informations sur ceux-ci.

# Activité quotidienne

Première idée: Introduire dans le workflows du dépôt principal une méthode qui permet de faire fonctionner les workflows des dépôts cibles et de récupérer les résultats nécessaires.

Problème 1: Comment agir sur un dépôt dont on a les droits depuis un autre dépôt qui nous appartient également?

solution utilisée: utilisation d'un TOKEN pour faire un commit vide sur l'autre répertoire. Le workflows du répertoire cible possède une configuration permettant de se lancer à chaque commit.


