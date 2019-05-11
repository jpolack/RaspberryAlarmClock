FROM node:10.15.3-alpine

WORKDIR /code

COPY . .

RUN npm ci

EXPOSE 3000

CMD [ "npm", "start" ]