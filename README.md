[![Docker Automated buil](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?maxAge=2592000)](https://hub.docker.com/r/devopsopen/docker-log-es/)

# Logging Service - Elasticsearch
Elasticsearch Docker Image for Logging Service of Open DevOps Pipeline.

# docker pull
docker pull devopsopen/docker-log-es

# docker run
docker run -d -p 9200:9200 -p 9300:9300 -v /esdata:/data --name Elasticsearch devopsopen/docker-log-es
