FROM mongo:latest

COPY init.json /init.json
CMD mongoimport --host mongo-leaflet --db leaflet_map --collection layercollection --type json --file /init.json --jsonArray
