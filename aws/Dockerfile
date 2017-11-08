FROM bartleboglehegarty/docker:8.2.1-bare

# Add AWS CLI
RUN \
    mkdir -p /aws && \
    apk -Uuv add groff less python py-pip && \
    pip install awscli && \
    apk --purge -v del py-pip && \
    rm /var/cache/apk/*

VOLUME ["/root/.config"]
