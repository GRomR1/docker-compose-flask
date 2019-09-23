# The next example of usage docker in web development.

This example presents a basic usage of [Docker Compose](https://docs.docker.com/compose/) tool.

It helps to deploy a previous simple app [docker-flask-hello](https://github.com/GRomR1/docker-flask-hello).

## Build and run container

Docker-compose reads config from file `docker-compose.yml` and runs container with command:
```shell script
docker-compose up
```

Add an argument `-d` to run container in background.

## Open application

Just open next URL in browser: [http://localhost:80](http://localhost:80)