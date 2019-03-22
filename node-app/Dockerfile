FROM node:carbon

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY src /app

EXPOSE 3000
CMD [ "node", "server.js" ]