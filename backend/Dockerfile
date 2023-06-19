FROM node:lts-buster-slim

COPY . /app

WORKDIR /app

RUN cp .env.example .env

EXPOSE 5000

RUN npm install --force

CMD ["npm","start"]