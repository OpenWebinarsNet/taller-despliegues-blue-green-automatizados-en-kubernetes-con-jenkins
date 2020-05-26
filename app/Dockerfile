FROM node:10.19.0-stretch-slim

COPY . /app
WORKDIR /app

RUN npm install
ENTRYPOINT ["node", "/app/app.js"]
