# Docker Project ESGI 2021

[Ce tutoriel](https://medium.com/swlh/how-to-create-your-first-mern-mongodb-express-js-react-js-and-node-js-stack-7e8b20463e66) est le projet react que l'on a récupéré.

`cd server && docker build -t api-server . && cd ..` depuis la racine pour construire l'image du serveur.

`cd client && docker build -t react-app . && cd ..` depuis la racine pour construire l'image react-app.

Faire `docker compose up -d` depuis root pour lancer les containers en mode deamon.

Faire `docker compose down` depuis root pour stopper les containers et les supprimer.
