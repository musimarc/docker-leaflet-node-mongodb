docker run -itd -p 3000:3000 --link mongo-leaflet:mongo-leaflet -v /opt/docker-leaflet-node-mongodb/node/src:/appli2 node-test

TODO:
Passer le docker-compose en V2
Ajouter le service application
Revoir le formatage des vues pug
Corriger le problème de chargement des données Json 
