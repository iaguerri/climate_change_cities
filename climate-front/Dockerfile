## build VUE Project
FROM node:latest

WORKDIR /climate-front

ENV PATH /climate_front/node_modules/.bin:$PATH

COPY package.json /climate_front/package.json

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]