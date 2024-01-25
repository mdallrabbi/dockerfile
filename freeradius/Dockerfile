FROM alpine:latest
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk --no-cache add \
    freeradius \
	freeradius-python \
	freeradius-radclient \
	freeradius-sql \
	freeradius-sqlite \
	openssl-dev \
	python2 \
	sqlite

ENTRYPOINT [ "radiusd" ]
CMD [ "-xx","-f" ]
