FROM node:22-alpine

COPY ./payload-app/ /payload-app/

WORKDIR /payload-app

RUN corepack enable pnpm

RUN npm install --verbose

# RUN cp .env.example .env

ENTRYPOINT [ "npm", "run", "dev" ]