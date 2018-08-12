FROM node:8.11.3

RUN apt-get update && \
  apt-get install -y \
    libgtk2.0-0 \
    libnotify-dev \
    libgconf-2-4 \
    libnss3 \
    libxss1 \
    libasound2 \
    xvfb

WORKDIR /app

COPY . /app

RUN npm i

EXPOSE 8080

CMD ["npm", "run", "serve"]