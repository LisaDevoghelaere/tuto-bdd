# Base de Données
## Se connecter à phpmyadmin depuis Wamp
-allumer wamp en double cliquant dessus
-Dans la barre de navigation windows, faire un clique gauche sur l'icône (devenue verte) et sélectionner phpmyadmin.
-Une page s'ouvre sur votre naivigateur pour vous permettre de vous connecter.
-Exécuter directement en laissant "root" comme utilisateur et le mot de passe vide.
## Créer une base de donnée
Dans la colone de gauche vous trouverez l'arborescence de vos base de donnée. Il suffit de cliquer tout en haut sur l'icône "nouvelle base de données".
Son nom doit être écrit en minuscule sans caractère spéciaux. Si le nom que vous avez choisi se compose de plusurs mots, il faudra alors les séparer avec le tiret du 6 ou du 8. Afin de lire tous les caractères de la langue française, vous devez choisir **utf8_general_ci" dans le menu déroulant juste à droite du nom.
Appuyer sur créer.
## Créer une nouvelle table
Vous arriverez alors sur laquelle vous retrouverez les tables que vous avez créé (actuellement aucune donc) et un formulaire pour en créer une nouvelle. C'est donc ce que nous allons faire.
Comme pour la base de donnée puis après pour les champs (colones), il ne faut pas utiliser ni caractères sépciaux, ni capitale, ni *camelCase*. Ensuite, choisissez le nombre de colones dont vous avez besoin pour votre table. Pour ce faire, je vous conseille de préparer en amont sur une brouillon ou un tableur  votre base de données, votre travailn'en sera que plus facile après.
## Créer les champs (colones)
Nous allons à présent nommer les champs et entrer leurs caractéristiques. 
Vous avez donc créer votre table et voyez maintenant un tableau avec les colones suivantes :
-Nom
-Type
-Taille/valeurs
-Valeur par défaut
-Interclassement
-Attributs
-Null
-Index
-A_I
-Virtualité
-Déplacer une colone

Je vous conseille vivement (très, très vivement) de garder une colone (le première) pour la création d'un id (soit identifiant), cela vous permettra plus tard de pouvoir facilement cibler une ligne.
