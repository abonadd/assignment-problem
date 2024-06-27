FROM node:alpine

WORKDIR /src

COPY package.json /src

RUN npm install

EXPOSE 3000

COPY . /src

CMD [ "node","server.js" ]