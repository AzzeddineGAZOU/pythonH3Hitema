# Docker Cheat Sheet


## Check Docker version
```
docker --version
```

## List all containers
```
docker ps
```

## List all running containers
```
docker ps --all
```
## Run a Docker image
```
docker run [image]
```

##List all local images
```
docker image ls 
```
or
```
docker images 
```

## Pull an image
```
docker pull [image]
```

## Build a Docker image using a Dockerfile
```
docker build .
```
<!-- docker build --build-arg username=user --build-arg password=pwd123 . -->

<!-- docker exec -it MonContainer /bin/bash -->
