ARG ALPINE_VERSION

FROM alpine:${ALPINE_VERSION}

RUN apk update && \
  apk upgrade --no-cache && \
  apk add --no-cache \
    git \
    bash
