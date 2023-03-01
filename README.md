## Laravel 10.x with Docker

### Installation

1. Clone this repo
2. copy the `.env.example` as `.env`
3. run `./vendor/bin/sail up` or `docker-compose up -d`

### Settings

Here are the available settings for port:
- APP_PORT
- FORWARD_DB_PORT
- FORWARD_REDIS_PORT

#### Notes:
- Laravel Horizon is set already without package installed yet.
