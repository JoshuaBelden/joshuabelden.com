FROM mhart/alpine-node:12

WORKDIR /

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 80

CMD [ "node", "server.js" ]
