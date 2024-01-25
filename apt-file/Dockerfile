FROM debian:sid-slim
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apt-get update && apt-get install -y \
	apt-file \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

CMD [ "bash" ]
