FROM debian:bullseye-slim
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apt-get update && apt-get install -y \
	cheese \
	libgl1-mesa-dri \
	libgl1-mesa-glx \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "cheese" ]
