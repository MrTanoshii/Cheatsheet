<div align="center">
    <a href="https://www.docker.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" title="Docker" alt="Docker" width="64" height="64"></a>
</div>

## Table of Contents

- [Documentation](#book-documentation)

## :book: Documentation

Website: https://www.docker.com/

Docker Hub: https://hub.docker.com/

## All purpose tiny container

Alpine with tail - `tail -f /dev/null` keeps the container running indefinitely, allowing you to interact with it or run additional commands as needed.

```yaml
# docker-compose.yaml
services:
  alpine:
    image: alpine:latest
    command: tail -f /dev/null
```
