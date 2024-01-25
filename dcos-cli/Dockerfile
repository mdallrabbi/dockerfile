FROM alpine:latest
LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk --no-cache add \
	ca-certificates \
	python \
	py2-pip \
	&& pip install dcoscli

# path to the DCOS CLI binary
RUN echo 'export PATH=$PATH:/dcos/bin;' >> ~/.bashrc

ENTRYPOINT [ "dcos" ]
