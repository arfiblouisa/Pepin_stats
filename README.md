# Pepin_stats
Code python pour faire les statistiques annuelles de Pépin.

1- Créer un dossier vide nommé collectes

2- Mettre tous les fichiers CSV (attention pas excel) des collectes à traiter (collectes de l'année, du mois, ...). Le nom des fichiers n'a aucune importance, ne pas perdre de temps à les renommer. collecte (2).csv convient très bien par exemple.

3- Lancer le main.  
4 parties dans le main : 1- Importataion des packages (les installer si besoin). 2- Création d'un fichier combined_collects.csv qui concatène toutes les collectes. Ce fichier est créé automatiquement dans le dossier source de votre projet. 3- Des premières statistiques obtenues avec panda (peuvent être intéressantes pour le nombre moyen d'un produit commandé par personne par exemple). 4- Les statistiques (le plus intéressant) de toutes les collectes considérées avec certaines unités plus exotiques que les kgs. Partie à compléter !! Un deuxième fichier csv recap_produits_commandes.csv est créé, peut être exploité à la main/à l'oeil.