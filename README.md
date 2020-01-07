# B3 Devops - TP 1
## Info
- mail: nicolas.laroche@ynov.com
- github​_username: Laroche-Nicolas

----


### A propos du projet : 

##### Résumé : 
- Le projet consiste à découvrir l'utilisation de Docker avec un fichier docker-compose, et d'être en mesure de pourvoir
 générer (build) et lancer (run) une image fonctionnelle docker.
- L'image fonctionnelle contiendra au final une base de données Postgres, un serveur Node sous sa version 12.

##### Status : 
- Fonctionnel
  


 
 ### Installation :


- Cloner le repo sur votre PC et ouvrez un terminal de commande.
- Rendez vous dans le dossier `tp2-laroche-nicolas\docker` et saisissez : 


    docker-compose build && docker-compose up
>En cas d'echec saisissez la commande : npm install

- Le projet est maintenant installé sur votre poste ! 



####Vérification du bon fonctionnement : 
Pour vérifier si le projet est bien en cours de fonctionnement d'une manière simple, rendez vous dans votre navigateur.

Puis tapez ces adresses URL : 


    http://localhost:8080/api
    
La réponse qui doit vous être fournie est : 


    {"message":"Hello World !"}


### Et enfin 

Si vous souhaitez arreter l'image docker saisissez la commande : 


    docker-compose down



