FROM alpine:latest
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk add --no-cache \
	ca-certificates \
	py-boto


COPY ./reset-cache.py /bin/reset-cache.py

CMD [ "/usr/bin/python", "/bin/reset-cache.py" ]
