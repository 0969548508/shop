<p align="center"><img src="https://topdev.vn/assets/img/logo.png" width="300"></p>

## About TopDev

### Technology used
This is a basic environment built using Docker Compose. It consists following:

| service | version | Port |
|---------|---------|-----|
| Laravel | 6.0.2   |      |
| Nginx | latest | 80, 443 |
| PHP | 5.6.`*`, 7.1.`*`, 7.3.`*` | 9056, 9071, 9072 |
| MariaDb | latest | 3306 |
| Mongodb | 4.0 | 37017 |
| Redis | latest | 6379 |
| ElasticSearch | 7.4.* | 9200, 9300 |
| Supervisor | latest | |
| Rabbitmq | latest | 5672, 15672 |

## Config

1. Env

   Config environment symlink

```bash
    ln -sF $(pwd)/env/.env.local $(pwd)/.env
```

2. Local

```bash
    composer install
```

3. Production

```bash
    composer install
```

> Học tập - Cống hiến để phát triển
