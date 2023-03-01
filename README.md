## Laravel 10.x with Docker

### Installation

1. Clone this repo
2. copy the `.env.example` as `.env`
3. run `./vendor/bin/sail up` or `docker-compose up -d`

### Settings

Here are the available settings for port in your .env file:
- APP_PORT
- FORWARD_DB_PORT
- FORWARD_REDIS_PORT
- NGINX_HOST_HTTP_PORT and NGINX_HOST_HTTPS_PORT

### Development
- run `docker exec -ti laravel-10-dockerized-laravel.test-1 bash` or `./vendor/bin/sail {COMMAND}`
- after you went inside, then run `composer install`
- then `php artisan key:generate` and `php artisan migrate`

#### Notes:
- Laravel Horizon is set already without package installed yet.
