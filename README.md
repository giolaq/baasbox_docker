## BaasBox Dockerfile


This repository contains **Dockerfile** of [BaasBox](http://www.baasbox.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/joaobiriba/baasbox) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/java](http://dockerfile.github.io/#/java)


### Installation

1. Install [Docker](https://www.docker.com/).


2. Download [automated build](https://registry.hub.docker.com/u/joaobiriba/baasbox/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull joaobiriba/baasbox`

   (alternatively, you can build an image from Dockerfile: `docker build -t="joaobiriba/baasbox" github.com/joaobiriba/baasbox_docker`)



### Usage

    docker run -d -p 9000:9000 dockerfile/baasbox



After few seconds, open `http://<host>:9000` to see the welcome page.
