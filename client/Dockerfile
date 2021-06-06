FROM node:14.14.0-alpine as builder

WORKDIR '/app'

COPY ./package.json ./

RUN npm run build

COPY ./ ./

CMD ["npm","run","start"]