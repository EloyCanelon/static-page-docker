FROM node:19.5.0-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install 

COPY . /app

CMD ["node", "./src/app.js"]