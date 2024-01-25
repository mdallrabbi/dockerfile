FROM	ruby:alpine
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"
RUN	apk add --no-cache \
	libcurl

RUN	set -x \
	&& apk add --no-cache --virtual .build-deps \
	build-base \
	&& gem install cloudapp --no-document \
	&& apk del .build-deps

ENTRYPOINT	["cloudapp"]
