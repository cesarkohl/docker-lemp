# Docker LEMP

```
docker compose build
docker compose up -d
```

The root directory is: /src/public

This is configured at /nginx/conf.d/default.conf:7

```
root /var/www/public;
```

## Optional: Raw PHP

```
mkdir src
mkdir src/public
touch src/public/index.php
```

## Optional: Install Laravel

```
composer create-project laravel/laravel src
```
