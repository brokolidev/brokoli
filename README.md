<p align="center"><img src="https://brokoli.ml/images/logo.png"></p>

## About brokolidev

It is my personal blog and portfolio web site.
Also think of it as references for the technologies that I currently have and interested.

Go to Live website: [brokolidev](https://brokoli.ml)

## Technologies

-   **[Laravel 7](https://laravel.com/)**
-   **[Vue JS](https://vuejs.org/)**
-   **[Axios](https://github.com/axios/axios)**

## After git clone..

```
# install composer 
composer install

# put db info and etc..
cp .env.example .env 
php artisan key:generate
php artisan migrate

# Permission for the log directories
sudo chown -R $USER:www-data storage
sudo chown -R $USER:www-data bootstrap/cache
chmod -R 775 storage
chmod -R 775 bootstrap/cache
```
