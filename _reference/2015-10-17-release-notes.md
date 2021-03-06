---
title: Release notes
author: Everett Toews <everett.toews@rackspace.com>
date: 2015-10-17
permalink: docs/reference/release-notes/
description: Notes on Carina releases
topics:
  - docker
---

### November 25, 2015

#### What’s new

* [Docker Engine 1.9.1](https://github.com/docker/docker/releases/tag/v1.9.1)

### November 23, 2015

#### What’s new

* Enable bind mounting `/var/run/docker.sock` from host to container. e.g.

```
docker run -v /var/run/docker.sock:/var/run/docker.sock docker:1.9.0 docker ps
```

### November 13, 2015

#### What’s new

* [Docker Engine 1.9.0](https://github.com/docker/docker/releases/tag/v1.9.0)
* [Docker Swarm 1.0.0](https://github.com/docker/swarm/releases/tag/v1.0.0)
* 2 Factor Authentication

#### Known issues

* Overlay networking unsupported at this time
* Volume drivers unsupported at this time

### October 27, 2015

#### What’s new

* Hello World
* [Docker Engine 1.8.3](https://github.com/docker/docker/releases/tag/v1.8.3)
* [Docker Swarm 0.4.0](https://github.com/docker/swarm/releases/tag/v0.4.0)
