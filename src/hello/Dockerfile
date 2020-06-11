FROM node:12-alpine

WORKDIR /app

COPY package.json package.json

RUN npm i --production

COPY index.js index.js

CMD ["node", "index.js"]

