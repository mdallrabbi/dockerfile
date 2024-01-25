FROM python:3-alpine

LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk add --no-cache \
	mplayer \
	mpv

RUN pip install mps-youtube

ENTRYPOINT ["mpsyt"]
