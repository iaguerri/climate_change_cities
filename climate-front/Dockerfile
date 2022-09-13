## build VUE Project
FROM node:latest

WORKDIR /climate-front

ENV PATH /climate-front/node_modules/.bin:$PATH

COPY package.json ./

RUN npm install

EXPOSE 5003

CMD ["npm", "run", "dev"]