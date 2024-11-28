FROM node:22.11-slim

RUN apt-get update -y && apt-get install -y openssl procps

WORKDIR /home/node/app

USER node

CMD [ "tail", "-f", "/dev/null" ]