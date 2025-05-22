# Docker protocol buffer compiler using RoadRunner protoc plugin

## Introduction

A Docker image containing the Protocol Buffer compiler using RoadRunner protoc plugin.
Published as [hungthai1401/roadrunner-protoc](https://hub.docker.com/r/hungthai1401/roadrunner-protoc).

## Usage:

```bash
docker run --rm -v $(pwd):/protos hungthai1401/roadrunner-protoc \
    --proto_path=/protos \
    --php_out="/protos" \
    --php-grpc_out="/protos" \
    /protos/*.proto
```

### Thanks
- [keepsuit/docker-protoc](https://github.com/keepsuit/docker-protoc)
