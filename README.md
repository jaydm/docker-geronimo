# docker-geronimo

Build a docker image for running Apache Geronimo.

# Usage

An example command for running the Docker image.

```shell
docker run -t -p 8080:8080 jaydm/geronimo:2.2.1
```

# Building

Very basic overview of how to start building this with Docker.
Refer to http://docker.io for more information on developing Docker images.

```shell
git clone git@github.com:jaydm/docker-geronimo.git
cd docker-geronimo
git checkout geronimo-2.2.1
docker build -t="yourusername/geronimo:2.2.1" .
```
