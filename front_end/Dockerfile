FROM alpine

LABEL maintainer="eagr1999@gmail.com"

RUN apk add --update nodejs nodejs-npm

COPY . /src

WORKDIR /src

RUN npm install

EXPOSE 5600

ENTRYPOINT ["node", "./index.js"]