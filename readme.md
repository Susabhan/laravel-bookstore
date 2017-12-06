#Setup:

##1. install dependencies via composer
composer install

##2. generate application key
php artisan key:generate

##3. run migrations:
php artisan migrate

##5. make files publicly accessible
php artisan storage:link

##6. run on localhost
php artisan serve