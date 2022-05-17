FROM python:3.6-alpine3.9

RUN apk update && apk add git

RUN git clone https://github.com/Mripumpkin/adbtest.git
#ADD ./ADBHoney /

WORKDIR ADBHoney
COPY entrypoint.sh /
RUN chmod +x /

ENTRYPOINT ["/entrypoint.sh"]
