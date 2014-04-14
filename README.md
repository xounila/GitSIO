Git par la pratique
===================

* Mettez vous en binôme.
* [Installez Git et configurez-le pour GitHub](http://help.github.com/set-up-git-redirect/)
* Dupliquez (*fork*) le projet GitSIO dans votre espace public.
* Récupérez sur votre disque dur les sources du projet.

        git clone https://github.com/SebInfo/GitSIO.git

* Indiquez le dépôt officiel :

        cd GitSIO
        git remote add official https://github.com/votrecompte/GitSIO.git 

* Sur votre disque dur, ajoutez à la fin de ce fichier le prénom et le nom d'un des membres du binôme. La ligne doit commencer par une étoile. Corrigez la liste pour que la dernière ligne se termine par un point et les autres par des virgules.
* Faites une révision :

        git add README.md
        git commit

* Publiez-la dans votre espace public:

        git push

* Dans GitHub faites une demande d'intégration (*pull request*). 
* Ajoutez le prénom et le nom de l'autre membre du binôme selon les mêmes règles que tout à l'heure.
* Faites une révision :

        git add README.md
        git commit

* Mettez à jour votre disque dur jusqu'à ce que vous récupériez les modifications de quelqu'un d'autre.

        git pull official master

* Réglez le conflit. Modifiez la mise en page de la liste pour qu'elle soit correcte.
* Une fois que le conflit est réglé par une révision, publiez l'ensemble des révisions dans votre espace public :

        git push

* Dans GitHub faites une demande d'intégration (pull request).

Liste des étudiants ayant réussi ce TP
--------------------------------------


* Sebastien Inion,
* Jules Bemé,
* Maxime SARRATO,
* Cédric Lefèvre,
* Florian Lecoeuche,
* Jordy Guilbert,
* Adrien Expert,
* Loris Venturelli,
* Valentin Boyer,
* Sylvain Pastor,
* Lannes Mathieu,
* Sitan Coulibaly,
* Maxime Edwards,
* Dazzan Edwin,
* Julien Martinez,
* Alex Santos,
* Samir Weber,
* Sylvain Cazanave,
* Emmanuel Robert,
* Salord Jérôme,
* Lacomblez Alain.
