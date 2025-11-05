FROM node:25-alpine

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]
