You probably shouldn't use this unless you know what you're doing. 

You need to know your Starling Account ID, have a Starling Developer Account, and have a Personal Access Token.

Generate the Personal Access Token with the following permissions:
* account:read
* account-list:read
* balance:read

Run the docker container with the following environment variables
* ACCOUNT_UUID
* PERSONAL_ACCESS_TOKEN

Fetch the metrics from 127.0.0.1:9822

Docker Hub: https://hub.docker.com/r/devopstom/prometheus-starling-exporter

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/devopstom/prometheus-starling-exporter)
![Docker Pulls](https://img.shields.io/docker/pulls/devopstom/prometheus-starling-exporter)
