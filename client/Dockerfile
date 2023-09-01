FROM node:18-alpine

WORKDIR /app

EXPOSE 3000

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json ./

RUN npm install --silent

COPY . ./

CMD [ "npm", "run", "dev"]