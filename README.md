# # Use laradock

### Installation
```sh
$ laravel new <Project Name>
$ cd <Project Name>
$ git init
$ git clone https://github.com/Laradock/laradock.git
$ cd laradock
$ cp env-example .env
```
Setting .env
```sh
NGINX_HOST_HTTP_PORT=8001
NGINX_HOST_HTTPS_PORT=8443

MYSQL_PORT=3307
```

```sh
$ docker-compose up -d nginx php-fpm mysql phpmyadmin redis
$ docker-compose ps
$ docker-compose exec workspace bash
$ mysql -u root -p
$ ALTER USER root IDENTIFIED WITH mysql_native_password BY 'root';
```

### Plugins

| Plugin | README |
| ------ | ------ |
| laradock | [website][PlGh] |

   [PlGh]: <http://laradock.io/introduction/>
