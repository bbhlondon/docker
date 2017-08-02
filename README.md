> Generic docker images useful for CI and other purposes

Based on official distros, preloaded with the tooling needed for BBH workflows. All include the tools required for use in CircleCI v2.

Note there is no `latest` tag as these builds are potentially very different from each other - so tag is required.

Listed on the Docker Hub at [bartleboglehegarty/docker](https://hub.docker.com/r/bartleboglehegarty/docker/)

Distros available:

| Tag | Base Distro | Base Distro Version | Base Distro link | Additions |
| --- | --- | --- | --- | --- |
| node-8.2.1-alpine | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `awscli` |
