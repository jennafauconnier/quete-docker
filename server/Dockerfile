FROM node:lts-alpine

# RUN te permet d'exécuter une commande comme tu le ferais dans ton terminal.
RUN mkdir /app

# WORKDIR définit un répertoire de travail
WORKDIR /app

# COPY copie le fichier indiqué de ta machine dans l'image.
COPY package*.json ./

RUN npm i

COPY src src

# CMD permet de démarrer mon application dans Docker
CMD npm start