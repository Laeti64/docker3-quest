FROM node:lts-alpine

# Create app directory
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src

CMD npm start