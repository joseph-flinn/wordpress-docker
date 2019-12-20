## Wordpress Docker Compose

This is a docker compose setup for building or working on wordpress sites by 
using docker. It is a very simple setup that does not include things like a
separate webserver container or a letsencrypt container to be a production level
project. THIS IS FOR DEVELOPMENT ONLY!!

The project needs an .env to run correctly. Please see the .env.example file:
```
MYSQL_ROOT_PASSWORD=password
MYSQL_USER=user
MYSQL_PASSWORD=password
MYSQL_DATABASE=database

WORDPRESS_DB_NAME=database
STAGING_URL=url.staging

WORDPRESS_DIR=wordpress_directory
```

This can be copied to an .env file and saved locally. The .env file is ignored 
by git so that secrets are not shared with the rest of the world.