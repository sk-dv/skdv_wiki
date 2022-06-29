### docker 

build docker image

```
docker build -t <image-name> .
```

run container built

```
docker run -it -p 3000:3000 skdv
```

list docker images

```
docker image ls
```

list all docker container 

```
docker ps -a
```

delete docker image

```
docker rmi <image-id>
```

delete docker container

```
docker rm <container-id>
```