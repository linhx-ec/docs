# Development

## Start docker

```shell
docker compose -f ./docker-compose.dev.yml up
```

Setup replica set after the mongo container has completely started.

```shell
docker exec -it <mongo-container-id> sh /scripts/init.sh
```
