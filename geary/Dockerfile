FROM debian:bullseye-slim
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apt-get update && apt-get install -y \
	geary \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "geary" ]
