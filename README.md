docker run -itd -p 3000:3000 --link mongo-leaflet:mongo-leaflet -v /opt/docker-leaflet-node-mongodb/node/src:/appli2 node-test
http://denelius.com/leaflet-node-mongodb/
TODO:
Passer le docker-compose en V2
Ajouter le service application
Revoir le formatage des vues pug
Corriger le problème de chargement des données Json

Chargement des données à partir de ce lien:
http://stackoverflow.com/questions/31210973/how-do-i-seed-a-mongo-database-using-docker-compose 
