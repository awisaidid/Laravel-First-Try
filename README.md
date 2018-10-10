# Laravel-First-Try

## First Setup

Clone project
` git clone https://github.com/awisaidid/Laravel-First-Try.git`

then enable writing permission for logs

```sudo chmod -R gu+w theme1
sudo chmod -R gu+w theme1/storage```

Generate  .env file and generate keys


```cp .env.example .env
php artisan key:generate
php artisan config:cache
composer dump-autoload```

run on server
`php artisan serve`

it will be available on (localhost:8000)[localhost:8000]
