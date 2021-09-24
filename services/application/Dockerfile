FROM node:alpine

WORKDIR /usr/src/app

COPY package.json ./
COPY yarn.lock ./

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm", "start"]