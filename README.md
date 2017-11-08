> Generic docker images useful for CI and other purposes

Based on official Node/Apine distros, and preloaded with the tooling needed for BBH workflows. All include the tools required for use in CircleCI v2.

The `latest` tag will be the more recent NodeJS distro with the `bare` configuration of tools as listed below.

Listed on the Docker Hub at [bartleboglehegarty/docker](https://hub.docker.com/r/bartleboglehegarty/docker/)

Distros available:

| Tag | Base Distro | Additions |
| --- | --- | --- |
| 9.0.0-bare | [node:9.0.0-alpine](https://hub.docker.com/_/node/) | `bash` `git` `tar` `gzip` `ca-certificates` |
| 9.0.0-all | [bartleboglehegarty:9.0.0-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `awscli` `gcloud` `firebase` |
| 9.0.0-aws | [bartleboglehegarty:9.0.0-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `awscli` |
| 9.0.0-firebase | [bartleboglehegarty:9.0.0-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `firebase` |
| 9.0.0-gcloud | [bartleboglehegarty:9.0.0-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `gcloud` |
| 8.2.1-bare | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `bash` `git` `tar` `gzip` `ca-certificates` |
| 8.2.1-all | [bartleboglehegarty:8.2.1-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `awscli` `gcloud` `firebase` |
| 8.2.1-aws | [bartleboglehegarty:8.2.1-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `awscli` |
| 8.2.1-firebase | [bartleboglehegarty:8.2.1-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `firebase` |
| 8.2.1-gcloud | [bartleboglehegarty:8.2.1-bare](https://hub.docker.com/r/bartleboglehegarty/docker/) | `gcloud` |
