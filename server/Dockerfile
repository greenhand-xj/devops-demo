FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 5001

CMD [ "node", "server.js" ]