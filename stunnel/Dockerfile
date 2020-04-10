# Forked from https://github.com/vimagick

FROM alpine:edge

RUN apk add --no-cache stunnel openssl

COPY ./stunnel/entrypoint.sh /entrypoint.sh

VOLUME /etc/stunnel

ENTRYPOINT ["/entrypoint.sh"]