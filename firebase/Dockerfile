FROM bartleboglehegarty/docker:9.0.0-bare

# Add Firebase tools
RUN yarn global add firebase-tools
# Fix high UID error: https://circleci.com/docs/2.0/high-uid-error/
RUN chown -R `id -un`:`id -gn` .

VOLUME ["/root/.config"]
