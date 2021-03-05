# Trying out react and docker

## Testing

```
docker build -f Dockerfile.dev .

docker run -p 3000:3000 -v $PWD:/app $container 
```

## Build

```
docker build .
```

## Run

```
docker run -p 8080:80 $CONTAINER 
```

## TODO

docker-compose not working for me locally. Permissions inside container throw error with .eslintcache and don't really feel like patching when works fine in docker.
