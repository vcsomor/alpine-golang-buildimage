alpine-golang-buildimage
========================

This repository contains the sources for the following [docker](https://docker.io) base images:
- [`vcsomor/alpine-golang-buildimage`]

## Usage

This Image is intended to be used in multi-stage docker builds and is not for final or production use you can find more info
about multistage build in this [blog post](https://www.critiqus.com/post/multi-stage-docker-builds/)

```
FROM vcsomor/alpine-golang-buildimage

RUN go build *.go

```
## Developing and testing

```bash
# Pull image
git clone ssh://git@github.com/lacion/alpine-golang-buildimage.git
cd alpine-golang-buildimage

# Build
make build

# Test
```
