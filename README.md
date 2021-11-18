# Remote Desktop Ping Service

A simple service to echo requests via websockets, can be useful for measuring 
latency between clients and this service.

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
