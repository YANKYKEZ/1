FROM node

WORKDIR /app

COPY package*.json /app/

RUN npm install

COPY . /app/

RUN NPM build

EXPOSE 4000
CMD [ "npm", "start"]


