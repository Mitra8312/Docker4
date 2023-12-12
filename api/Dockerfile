FROM node:alpine

WORKDIR /time-app

COPY package*.json ./

RUN npm install 

copy . . 

EXPOSE 5000

CMD ["npm","run","dev"]