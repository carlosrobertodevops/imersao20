FROM node:22.12.0-slim

RUN apt update -y && \
    apt install openssl procps -y && \
    npm install -g @nestjs/cli@10.4.8 \
    npm install -g npm@11.0.0

USER node

WORKDIR /home/node/app

CMD [ "tail", "-f", "/dev/null" ]