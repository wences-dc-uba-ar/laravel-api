# laravel-api
laravel api test

# log:
```bash
# install composer
composer global require "laravel/installer"

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

```
tuto laravel api test:

* https://www.toptal.com/laravel/restful-laravel-api-tutorial
```bash
php artisan make:model Article -m
```
