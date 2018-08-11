FROM node:8.11.3-alpine

WORKDIR /app

COPY . /app

RUN npm i

EXPOSE 8080

CMD ["npm", "run", "serve"]