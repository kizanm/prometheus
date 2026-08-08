---
title: Installation
sort_rank: 2
---

## Using pre-compiled binaries

Pre-compiled binaries are available for most official Prometheus components.
Visit the [download section](https://prometheus.io/download) to find available
versions and platform-specific builds.

## Building from source

To build Prometheus components from source, refer to the available `Makefile`
targets in each component's repository.

## Using Docker

Official Prometheus images are available on
[Quay.io](https://quay.io/repository/prometheus/prometheus) and
[Docker Hub](https://hub.docker.com/r/prom/prometheus/).

Starting Prometheus with Docker is straightforward:

```bash
docker run -p 9090:9090 prom/prometheus
```
This command launches Prometheus with a default configuration and exposes the web interface on port 9090.
