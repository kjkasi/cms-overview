FROM node:22-alpine

COPY ./strapi-app/ /strapi-app/

WORKDIR /strapi-app

RUN npm install --verbose

ENTRYPOINT [ "npm", "run", "dev" ]