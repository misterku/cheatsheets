## Show containers
```
sudo docker ps -a —no-trunc
```

## Show logs for container
```
sudo docker logs <container>
``` 

## Tag and push docker image
```
docker image tag <image_id> <name:tag>
docker image push <name:tag>
```

## Show container stats
```
docker stats --no-stream
```

## Interactive mode
```
docker -it ....
```

## Set entrypoint
```
docker run --entrypoint <command> <container_id_> <arg1> <arg2> ....
```

## Inspect docker image
```
docker inspect <container_id>
```
