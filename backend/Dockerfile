FROM node:22-alpine3.18

WORKDIR /app/

COPY . .

RUN mkdir -p logs && mkdir -p upload && npm install

CMD [ "npm", "start" ]
