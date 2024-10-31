FROM node:18-slim

WORKDIR /

COPY package*.json ./

RUN npm install

COPY . .


CMD ["node", "server.js"]
