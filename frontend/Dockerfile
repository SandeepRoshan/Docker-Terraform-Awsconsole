FROM node:21-alpine

WORKDIR ./app

COPY package*.json ./

COPY ./public ./public

COPY ./src ./src

RUN npm i

EXPOSE 3000

CMD [ "npm", "start" ]



