# syntax=docker/dockerfile:1

FROM node:18
ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json", "./"]

RUN npm install

COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
