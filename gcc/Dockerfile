FROM debian:bullseye-slim
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apt-get update && apt-get install -y \
	gcc \
	libc6-dev \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*
