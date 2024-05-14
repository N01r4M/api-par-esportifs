# Base de données
Lors du développement, j’ai utilisé XAMPP pour la gestion de la base de données. Pour le télécharger, il suffit de se rendre sur ce lien et de choisir le bon fichier. 
Une fois l’application téléchargée et lancée, il faut allumer les modules “Apache” et “MySQL”.
 
Pour accéder à PHPMyAdmin, il suffit de se rendre sur ce lien : http://127.0.0.1/phpmyadmin/index.php 

# API
Pour récupérer l’API et la mettre en place, voici les étapes à respecter : 
-	Se rendre sur ce dépôt github : https://github.com/N01r4M/api-par-esportifs 
-	Ouvrir son cmd et noter la commande suivante : git clone https://github.com/N01r4M/api-par-esportifs.git 
-	Ouvrir un terminal de commande au niveau de la racine du projet et noter les commandes suivantes : 
	composer install --ignore-platform-reqs
	php bin/console doctrine:database:create
	php bin/console d:m:m
-	En vous rendant sur le lien suivant, vous devriez avoir accès à la base de données et toutes les entités qui lui correspondent : http://127.0.0.1/phpmyadmin/index.php
-	Vous pouvez lancer le serveur pour symfony à l’aide de la commande suivante : symfony serve (pour le stopper noter la commande : symfony server:stop)
-	Il vous suffit de vous rendre sur le lien suivant pour accéder à l’interface graphique et la documentation d’API Platform : http://127.0.0.1:8000/api 
