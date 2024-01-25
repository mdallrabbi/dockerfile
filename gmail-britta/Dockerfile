FROM	ruby:alpine

LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk add --no-cache \
	coreutils

RUN	set -x \
	&& apk add --no-cache --virtual .build-deps \
	build-base \
	&& gem install gmail-britta --no-document \
	&& apk del .build-deps
