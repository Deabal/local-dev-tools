# local-dev-tools

tool kits quick run in local for developing

## Attention

**DO NOT** use these tools in production environment.

Pay attention to the `ChangeMeHere!` in .env file.

## tools

- [x] MySQL
- [ ] PostgreSQL
- [x] Redis
- [ ] MongoDB
- [ ] Kafka
- [ ] RabbitMQ
- [ ] Elasticsearch
- [ ] ETCD
- [ ] Consul
- [ ] Jaeger

## MySQL

Default MySQL version is 8.0. Default port is 33306.

You can change the version / port in the `docker-compose.yml` file.

edit '.env' file to set the following variables for MySQL

### variables

- DB_DATABASE: database name
- DB_USER: database user
- DB_PASSWORD: database password
- DB_ROOT_PASSWORD: root password
- TIMEZONE: timezone

### run!

```shell
cd mysql
docker-compose up -d --build
```

## Redis

Default Redis version is 7. Default port is 36379.

### variables

- REDIS_PASSWORD: redis password

### run!

```shell
cd redis
docker-compose up -d --build
```
