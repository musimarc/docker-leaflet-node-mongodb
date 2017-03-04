FROM node:latest

RUN mkdir /app
WORKDIR /app

COPY src/leaflet_map/package.json /app
RUN npm install

COPY src/leaflet_map /app

EXPOSE 3000
CMD ["npm", "start"]
