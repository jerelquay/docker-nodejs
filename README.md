# docker-nodejs
Sample of building nodejs from a Dockerfile &amp; Running in container

## Building of the image
```shell
docker build -t nodejs-sample .
```

## Run the image
```shell
docker container run -p 80:3000 --rm -it nodejs-sample
```
