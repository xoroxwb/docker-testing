FROM alpine:3.10

RUN apk add --no-cache \
        perl

COPY overlay/ /

ENTRYPOINT ["/entrypoint"]
