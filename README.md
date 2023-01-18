# Docker-ACI 

Docker container with Azure ACI and Docker-in-Docker.

```
docker build --platform linux/amd64 --tag docker-aci .
```

```
docker run --rm -it --platform linux/amd64 \
    -v "$(pwd):/app" \
    -v /var/run/docker.sock:/var/run/docker.sock \
    docker-aci
```


