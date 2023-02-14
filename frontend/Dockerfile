FROM node:alpine

WORKDIR /app

EXPOSE 3000

COPY package*.json ./

RUN npm instal

COPY . .

CMD [ "npm", "run", "dev" ]