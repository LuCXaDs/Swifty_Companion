FROM node:20.9.0

EXPOSE 3000

WORKDIR /app

COPY ./package.json ./

RUN npm install

RUN npm install -g nodemon

COPY . .

CMD ["npm", "run", "start:dev"]