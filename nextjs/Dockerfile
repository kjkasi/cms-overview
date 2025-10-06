FROM registry.altlinux.org/p11/node:22.13.1

COPY ./my-app/ /my-app/

WORKDIR /my-app

RUN npm install --verbose

ENTRYPOINT [ "npm", "run", "dev" ]