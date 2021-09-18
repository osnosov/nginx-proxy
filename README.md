# Docker Compose nginx proxy

Used [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy)

## Running

Download

```console
git clone https://github.com/osnosov/nginx-proxy
```

Create Docker Network

```console
docker network create -d bridge nginx-proxy
```

Run docker-compose

```console
docker-compose up -d
```

Stop docker-compose

```console
docker-compose stop
```
