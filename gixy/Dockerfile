# Run gixy command line tool for static nginx analysis:
# https://github.com/yandex/gixy
#
# Usage:
# 	docker run --rm -it \
# 		-v /etc/nginx:/etc/nginx \
#		r.j3ss.co/gixy /etc/nginx/nginx.conf
#
FROM python:2-alpine

LABEL maintainer "MD ALL RABBI <md.all.rabbi@outlook.com>"

RUN pip install gixy

ENTRYPOINT ["gixy"]
