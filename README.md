# Portainer compose setup

A simple setup to deploy Portainer with custom templates.

This setup also comes with [watchtower](https://hub.docker.com/r/v2tec/watchtower/) to automatically upgrade Portainer version :)

# Requirements

1. Install [Docker](http://docker.io).
2. Install [Docker-compose](http://docs.docker.com/compose/install/).
3. Clone this repository

# Usage

The default configuration will connect Portainer against the local Docker host, using an nginx container (port 80).

Run it:

```
$ docker-compose up -d
```

And then access Portainer by hitting [http://localhost/portainer](http://localhost/portainer) with a web browser.

# Configuration

## Offensive templates

All templates should be loaded and readily made available