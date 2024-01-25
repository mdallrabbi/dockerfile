FROM alpine:latest

LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN apk --no-cache add \
	openvpn

RUN mkdir /usr/share/openvpn
RUN cp /etc/openvpn/* /usr/share/openvpn/

WORKDIR /etc/openvpn
ENTRYPOINT ["openvpn"]
