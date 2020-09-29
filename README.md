# docker-7.2-apache

## build & run
```sh
  docker build -t some-apache .
  docker run -d -v foo:/var/www/html --link mysql:mysql --network some-network -p 8082:80 some-apache
```

