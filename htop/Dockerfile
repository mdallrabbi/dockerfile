# htop in a container
#
# docker run --rm -it \
# 	--pid host \
# 	jess/htop
#
FROM alpine:latest
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk --no-cache add \
	htop

CMD [ "htop" ]
