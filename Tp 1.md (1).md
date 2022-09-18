## Compte rendu TP 1


## Exercice 2 :

 ## Manuel

 - Question 1 
		Pour commencer on rentre la commande "man which" pour avoir le manuel de fonctionnement de la commande which. Cela nous explique que which permet d'afficher le chemin d'accès du fichiers ou du lien qui sera exécuter dans l'environnement actuel.
		
 - Question 2 :



 - Question 3 :
	 Lorsqu'on est dans le manuel tout en bas s'affiche une phrase indiquant les commandes pour l'aide ou pour quitter. On peut voir que la touche pour quitter est "q". 

 - Question 4 :
	 
	 Pour afficher la page de la section 6 il faut taper la commande man 6 intro. Cette page parle des jeux disponibles sur Linux.

 ## Navigation dans l'arborescence des fichiers

 - Question 1
	 
	 Pour aller dans le dossier /var/log il faut taper la commande cd /var/log.

 - Question 2 
 
	 Pour remonter dans le dossier parent /var en utilisant un chemin relatif, la commande est cd .. 

 - Question 3 

	Pour retourner le dossier personnel il faut taper cd 

 - Question 4 
 
	 Pour revenir au dossier précédent sans utiliser de chemin il faut utiliser la commande cd -

 - Question 5
	 
	 En essayant d'accéder au dossier /root en utilisant la commande cd /root, on remarque qu'on ne dispose pas des permissions nécessaires pour accéder au dossier.

 - Question 6 

	On nous demande d'accéder au dossier /root en utilisant la commande sudo cd mais on remarque que cela ne marche pas car cd n'est pas un binaire mais un shell built-in

 - Question 7
 
	 Une fois qu'on est dans notre dossier personnel, pour créer le premier dossier il faut utiliser la commande "mkdir dossier1", on peut ensuite répéter la même action pour le dossier2. Puis il faut rentrer dans le dossier1 avec "cd /dossier1" et dans le dossier créer le fichier 1 avec la commande "touch fichier1". Pour revenir au début il faut faire cd ..
	 Par la suite il faut maintenant aller dans le dossier 2, créer les deux dossiers "dossier2.1" et "dossier2.2". Rentrer dans le dossier2.2 et créer les deux fichiers "fichiers2" et "fichiers3".

 - Question 8
 
	Il est impossible de supprimer "fichier1" car il n'arrive pas à le trouver, il faut dans ce cas la indiquer le chemin entier.

 - Question 9
 
	 On peut supprimer un dossier à l'aide de la commande "rmdir"

 - Question 10
	 
	 Le dossier ne peut pas être supprimé car il contient d'autres dossiers et fichiers à l'intérieur.

 - Question 11
 
	 Pour supprimer dossier2 et son contenu il faut utiliser la commande "rm -Rf dossier2"

## Commandes importantes

 - Question 1
 
	 Pour afficher l'heure on peut utiliser la commande "date". 
	 La commande time sert à afficher et régler l'heure  actuelle du système.
 
 - Question 2
	
	Les fichiers commençant par un point sont des fichiers masqués.
	
	
 - Question 3
	 
	 Le programme "ls" se situe dans /usr/bin
	 
 - Question 4
	
	En tapant la commande "man ll" on peut essayer de voir s'il existe une entrée de manuel pour la commande ll, en validant on peut voir qu'il n'existe pas d'entrée de manuel pour "ll".
	
 - Question 5
 
	 
 - Question 6
	
	La commande ls permet d'afficher les dossiers 
 
 - Question 7
	 Pour connaître le chemin complet du dossier courant il faut utiliser la commande "pwd".
	 
 - Question 8
	 La commande echo 'bip' > plop exécutée la première fois permet d'écrire bip dans plop, puis comme nous utilisons un seul chevron cela écrase le contenu de plop et réécris de nouveau plop.
	 
 - Question 9
	 La commande echo 'bip' >> plop exécutée la première fois permet d'écrire bip dans plop, mais avec deux chevrons lors de la deuxième exécution, le contenu de plop ne sera pas écraser et le deuxième bip sera écrit à la suite.
	 
 - Question 10
	 La commande sleep 10 | echo 'toto' permet d'afficher toto et de créer un delay de 10 sec
	 
 - Question 11
	 La commande File sur Linux vous permet d’obtenir des informations sur le type de fichier.
	 
 - Question 12
	 On remarque qu'en modifiant le contenu du fichier original cela modifie également le fichier lien_phy.
	 Aucune, le fichier lien_phy est conservé ainsi que son contenu.
	 
 - Question 13
	 En modifiant le contenu de lien_phy cela modifie également celui de lien_sym et inversement également.
	 Si on supprime le fichier lien_phy cela supprime également lien_sym
	
 - Question 14
	 Avec ctrl ^X on peut sortir et reprendre le défilement à l'écran
	 
 - Question 15
	 Pour afficher les 5 premières lignes il faut utiliser la commande head -5 /var/log/syslog.
	 Pour les 15 dernières c'est la commande tail -15 /var/log/syslog
	 
 - Question 16
	 La commande vous permet de scruter le monde caché des processus de démarrage Linux
	 
 - Question 17
	 Pour ouvrir le manuel il suffit de taper man passwd, il contient les différents chemins d'accès.
	 
 - Question 18
	 Il est possible de trier avec la commande "sort"
	 
 - Question 19
	 Avec la commande getent passwd | wc -l on peut voir combien d'utilisateurs ont des comptes.
	 
 - Question 20
	 
 - Question 21 
	 
## Exercice 3 

 - Question 1 
	 cp /var/log/syslog /home/User/log.txt permet de copier le fichier dans le dossier personnel. Ensuite il ne reste plus qu'à l'ouvrir avec nano en faisant nano log.txt
	 
 - Question 2
	 Pour remplacer toutes les occurences du mot kernel par le mot noyau, il faut utiliser le raccourci ctrl + \
	 
 - Question 3
	 
	 
 - Question 4
	 Pour annuler il faut utiliser le raccourci Alt + U
	 
 - 

 

	

	
	 

	

 

 
	 

 
	 

 
	 

	 

`

