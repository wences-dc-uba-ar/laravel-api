# laravel-api
laravel api test

deploy after cloning:
```bash
# install composer
composer global require "laravel/installer"

#install dependencies
composer install

# copy default env
[ -s .env ] || cp .env.example .env

# generate key
php artisan key:generate

# serve app
php artisan serve
```

log following:
* https://www.toptal.com/laravel/restful-laravel-api-tutorial
```bash
# create laravel skeleton
laravel new sarasa

# move to ./
mv sarasa/{.,}* .
rmdir sarasa

# copy default env
[ -s .env ] || cp .env.example .env

# generate key
php artisan key:generate

# serve app
php artisan serve

php artisan make:model Article -m
```
