Projet 1 : Wordpress
Script qui automatise l'installation d'un wordpress avec la base de donn�es MySQL sur une VM � part. Le script doit se lancer depuis une machine seule et via ssh. Les utilisateurs du ssh devront �tre cr�es avec les droits.

Guide d�installation : 
Plac� les documents suivant dans un m�me dossier.
-	script.sh
-	sql.sh
-	wp.sh
Lancement :
Le lancement du script est param�trable et se lance � partir du script.sh.
Par d�fauts les valeurs sont les suivantes :
-	-n : dbname=wordpress
-	-u : dbuser=wpuser 
-	-p : dbpwd=wppwd
-	-h : dbhost=172.16.10.5
-	-s : wpsource=https://wordpress.org/latest.tar.gz

Pour le lancement sans param�tre : PATH/script.sh 
Pour le lancement avec param�tre : PATH/script.sh -h 192.168.10.2    
