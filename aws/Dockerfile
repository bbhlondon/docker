FROM bartleboglehegarty/docker:9.0.0-bare

# Add AWS CLI
RUN \
    mkdir -p /aws && \
    apk -Uuv add groff less python py-pip && \
    pip install awscli && \
    apk --purge -v del py-pip && \
    rm /var/cache/apk/*

VOLUME ["/root/.config"]
