# Dockerized Laravel

## Creating laravel project:
Before creating laravel project, create *src* folder first

`docker-compose run --rm composer create-project --prefer-dist laravel/laravel .`

## Run Laravel App
`docker-compose up -d --build server`

## Run Artisan
`docker-compose run --rm artisan migrate`

`docker-compose run --rm artisan key:generate --ansi`