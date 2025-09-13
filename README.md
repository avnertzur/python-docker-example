# python-docker-example
simple python FAST API app as docker container

## Build the docker image
```
docker build -t my-fastapi-app .
```

## Run the continer
```
docker run -d -p 8000:8000 --name my-fast-api my-fastapi-app
```
