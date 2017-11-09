FROM bartleboglehegarty/docker:9.0.0-bare

# Add Firebase tools
RUN yarn global add firebase-tools
# Fix high UID error: https://circleci.com/docs/2.0/high-uid-error/
RUN chown root /usr/local/share/.config/yarn/global/node_modules/grpc/src/node/extension_binary/node-v57-linux-x64/grpc_node.node

VOLUME ["/root/.config"]
