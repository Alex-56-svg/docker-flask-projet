# projet Docker Flask

## Objectif
 Creation d'une image docker pour une application flask
 access au serveur  hello-world et ngnix(8081) pour les tests

#Construction de l'image 
 '''bash
docker build -t flask-app

#lancement du container
docker run -d -p 5000:5000 flask-app

#acces serveur
http:localhost:5000 
