First we are defining some required environment variables.

The .env and docker-compose.yml are expected in the current working directory, 

```
NEXTCLOUD_ADMIN_USER=admin
NEXTCLOUD_ADMIN_PASSWORD=

POSTGRES_PASSWORD=
```

Finally start the containers in the background

docker-compose up -d



[DEBUG]

docker-compose exec app bash

docker-compose logs app



### for more specific configuration reference 

https://github.com/owncloud-docker/server

https://github.com/nextcloud/docker

https://github.com/libresh/compose-nextcloud/blob/master/docker-compose.yml

