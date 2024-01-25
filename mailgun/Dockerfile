FROM r.j3ss.co/curl
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk add --no-cache \
	bash

COPY sendemail /usr/bin/sendemail

ENTRYPOINT [ "sendemail" ]
