> Generic docker images useful for CI and other purposes

Based on official Node/Apine distros, and preloaded with the tooling needed for BBH workflows. All include the tools required for use in CircleCI v2.

Listed on the Docker Hub at [bartleboglehegarty/docker](https://hub.docker.com/r/bartleboglehegarty/docker/)

Distros available:

| Tag | Base Distro | Base Distro Version | Base Distro link | Additions |
| --- | --- | --- | --- | --- |
| 8.2.1-all | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `awscli` `gcloud` `firebase` |
| 8.2.1-aws | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `awscli` |
| 8.2.1-firebase | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `firebase` |
| 8.2.1-gcloud | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `gcloud` |
| 9.0.0-all | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `awscli` `gcloud` `firebase` |
| 9.0.0-aws | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `awscli` |
| 9.0.0-firebase | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `firebase` |
| 9.0.0-gcloud | NodeJS | 8.2.1 | [node:8.2.1-alpine](https://hub.docker.com/_/node/) | `git` `tar` `gzip` `ca-certificates` `gcloud` |
