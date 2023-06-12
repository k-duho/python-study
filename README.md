Check docker compose config

```sh
docker compose -f local.yml config
```

If you are running any arm based MacBook.
Run this command

```sh
export DOCKER_DEFAULT_PLATFORM=linux/amd64
```

Build docker image again

```sh
docker compose -f local.yml up --build -d --remove-orphans
```
