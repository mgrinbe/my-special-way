FROM node:carbon

WORKDIR /opt/app/myspecialway
COPY yarn.lock package.json ./
RUN yarn --production
COPY ./dist ./

ENTRYPOINT node main