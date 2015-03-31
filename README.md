## Ruby

This repository contains experimental **Dockerfile** of [Ruby](https://www.ruby-lang.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/denvazh/ruby/).

At the moment it uses system default `ruby-2.1.5p273` installed directly with apk package manager.

### Base Docker Image

* [gliderlabs/alpine:3.1](https://registry.hub.docker.com/u/gliderlabs/alpine/)

### Tags

* `latest` (default): Ruby 2.1.5p273 which is an alias to `2.1.5p273`
* `2.1.5p273`: Ruby 2.1.5p273

### Installation

1. Install [Docker](https://www.docker.com/)

2. Download [automated build](https://hub.docker.com/u/denvazh/ruby) from public registry: `docker pull denvazh/ruby`
  
  (alternatively, one can build an image `docker build -t="denvazh/ruby" github.com/denvazh/ruby`)
