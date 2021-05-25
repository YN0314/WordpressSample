### setup

- create .env file

```
# timezone
TZ=Asia/Tokyo
# mysql root password
DB_ROOT_PASS=p@ssw0rd
# mysql database
DB_NAME=wordpress
# mysql db_user
DB_USER=wordpress
# mysql db_password
DB_PASS=wordpress
# wordpress database host
WORDPRESS_DB_HOST=db
# wordpress database user
WORDPRESS_DB_USER=wordpress
# wordpress database password
WORDPRESS_DB_PASSWORD=wordpress
# wordpress database name
WORDPRESS_DB_NAME=wordpress
```

- docker up

```
docker-compose up -d --build
```

- access wordpress site
  - http://localhost:10080/
