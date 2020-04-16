# Sindock PHP

Complete deployment docker environment for any php monolithic application.

## Configuration

- Setup Docker Compose: `cp docker-compose-<your-env>.example.yml docker-compose.yml`
- Setup env: `cp .env.example .env`
- Start environment: `docker-compose up -d`

## Environment Variables

- HOST_USER_UID default is "1000"
- TZ time zone default is "Europe/Rome"
- DEFAULT_SINDRIA_USER_PASSWORD default is "sindria"
- NGINX_PHP_PM_MAX_CHILDREN Max number of child process for php-fpm pool default is "16"  
