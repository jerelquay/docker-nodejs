# docker-nodejs
Sample of building container from Dockerfile &amp; Running in container

## Building of the image
```shell
docker build -t jerelquay/nodejs-sample .
```

## Run the image
```shell
docker container run -p 80:3000 --rm -it jerelquay/nodejs-sample
```
