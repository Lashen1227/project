# Dockerfile for the API service
FROM node:20-alpine

RUN npm install -g nodemon

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 3001

CMD ["npm","run" ,"dev"]
