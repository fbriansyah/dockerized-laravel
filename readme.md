# Dockerized Laravel

## Creating laravel project:
`docker-compose run --rm composer create-project --prefer-dist laravel/laravel .`

All Laravel files will create in src folder

## Run Laravel App
`docker-compose up -d --build server`

## Run Artisan
`docker-compose run --rm artisan migrate`

`docker-compose run --rm artisan key:generate --ansi`