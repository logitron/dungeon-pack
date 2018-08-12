FROM cypress/base:8

WORKDIR /app

COPY package*.json /app/

RUN npm i -g npm

RUN npm i

EXPOSE 8080