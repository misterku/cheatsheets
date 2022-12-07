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