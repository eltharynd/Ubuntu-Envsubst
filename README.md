# Ubuntu + Envsubst

This is a simple image containing `ubuntu:latest` with preinstalled `gettext-base`.

It is published on [DockerHub](https://hub.docker.com/docker/eltharynd/ubuntu-envsubst) as `eltharynd/ubuntu-envsubst`.

## Building

```shell
docker buildx build --platform linux/amd64,linux/arm64 . -t eltharynd/ubuntu-envsubst
```

## Publishing

```shell
docker push eltharynd/ubuntu-envsubst
```
