## build VUE Project
FROM node:latest

WORKDIR /climate-front

COPY package*.json ./

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]
# ## build VUE Project
# FROM node:16.17.0
# WORKDIR /climate-front
# # ENV PATH /climate-front/node_modules/.bin:$PATH
# COPY ./package*.json ./
# RUN npm install -g
# COPY . .
# EXPOSE 3000
# CMD [ "npm", "run","dev"] 


