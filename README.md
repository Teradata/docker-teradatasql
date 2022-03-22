# docker-teradatasql

A Docker image that extends the official Python image and adds `teradatasql`.
## Building

The dockerfile is parametrized. You need to specify PYTHON_VERSION to build the image:

```
docker build --build-arg PYTHON_VERSION=3.9  -t teradata/teradatasql:latest .
podman build --build-arg PYTHON_VERSION=3.9  -t teradata/teradatasql:latest .
```