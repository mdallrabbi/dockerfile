FROM node:alpine

LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk add --no-cache git
RUN git clone --branch master --depth 1 https://github.com/hugomd/parrot.live.git /src
WORKDIR /src
RUN npm install
CMD ["node","index.js"]
