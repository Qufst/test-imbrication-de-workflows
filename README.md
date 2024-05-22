# test-imbrication-de-workflows

# Objectif 

L'objectif de ce dépôt est de trouver une méthode pour centraliser dans un dépôt le lancement de plusieurs autres dépôts et de récupérer des informations sur ceux-ci.

# Activité quotidienne

Première idée: Introduire dans le workflows du dépôt principal une méthode qui permet de faire fonctionner les workflows des dépôts cibles et de récupérer les résultats nécessaires.

Problème 1: Comment agir sur un dépôt dont on a les droits depuis un autre dépôt qui nous appartient également?

idée 1: Générer un Token permettant le contrôle sur les répertoires privés, (est-ce que ça signifie que ça ne fonctionne pas avec des répos publics, ou juste que les dépôts doivent nous appartenir?), et de pouvoir mettre à jour le 'github action workflows'.

