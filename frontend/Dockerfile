FROM node:22-alpine3.18

WORKDIR /app/

COPY package.json /app/package.json

RUN npm i -g pnpm

COPY . .

RUN pnpm i

CMD [ "npm", "start" ]
