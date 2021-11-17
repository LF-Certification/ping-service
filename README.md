# Remote Desktop Ping Service

A simple ping / echo service written in Go.
Can be used to calculate latency to guacamole.

### Run
```sh
make run
```


### Build
```sh
make build
```


### Run in docker locally
```sh
docker build . -f docker/Dockerfile -t rd-ping-service
docker-compose -f docker/docker-compose.yml up -d
```