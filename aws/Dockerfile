FROM node:8.2.1-alpine

# Add AWS CLI
RUN \
    mkdir -p /aws && \
    apk -Uuv add groff less python py-pip && \
    pip install awscli && \
    apk --purge -v del py-pip && \
    rm /var/cache/apk/*

# Packages for CircleCi compatibility
RUN apk add --no-cache git tar gzip ca-certificates

VOLUME ["/root/.config"]
