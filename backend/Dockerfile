FROM node:17-alpine

WORKDIR /nodeapp

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]