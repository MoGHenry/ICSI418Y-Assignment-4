FROM node:14

WORKDIR /icsi418-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
