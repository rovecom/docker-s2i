# docker-s2i

Docker image with based on docker:git (Docker in Docker) with source-to-image installed.

Source-to-image is a tool for building/building artifacts from source and injecting into docker images.

More information can be found here: https://github.com/openshift/source-to-image

# Where to find the images

https://hub.docker.com/r/rovecom/docker-s2i

# How to use it

We use this image as a build image it GitLab when utilizing s2i for building to actual image. This image is based on the `docker:git` image so it contains all tools for building and pushing images. 