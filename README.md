docker-buildagent-docker
========================

Teamcity agent + Docker

This image is Teamcity agent with access to Docker on host

Usage
=====

```
docker run -it --rm -v /var/run/docker.sock:/var/run/docker.sock sergeyzh/buildagent-docker
```