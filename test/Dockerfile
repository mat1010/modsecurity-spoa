FROM alpine:3.17.0

RUN apk add --no-cache bash tini curl

COPY ./curl.sh /

ENTRYPOINT ["tini", "--", "/curl.sh"]
