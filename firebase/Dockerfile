FROM bartleboglehegarty/docker:8.2.1-bare

# Add Firebase tools
RUN yarn global add firebase-tools
# Fix high UID error: https://circleci.com/docs/2.0/high-uid-error/
RUN chown -R `id -un`:`id -gn` . || true

VOLUME ["/root/.config"]
