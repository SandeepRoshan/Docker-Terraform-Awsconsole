FROM node:21-alpine

WORKDIR ./app

COPY package*.json ./

COPY ./server.js ./server.js

RUN npm i

EXPOSE 3000

CMD [ "node", "server.js" ]



