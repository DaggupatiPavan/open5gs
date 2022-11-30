FROM node:12.14.1-alpine3.9

RUN apk update && apk add git

RUN npm install && \
    npm run build

CMD npm run start

EXPOSE 3000
