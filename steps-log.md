# laravel Install:
```bash
composer global require "laravel/installer"

laravel new sarasa

mv sarasa/{.,}* .
rmdir sarasa

[ -s .env ] || cp .env.example .env

php artisan key:generate

php artisan serve

```
tuto laravel api test:

* https://www.toptal.com/laravel/restful-laravel-api-tutorial
```bash
php artisan make:model Article -m
```