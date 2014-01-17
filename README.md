habrahabr
=========

Laravel 4 web-application for Habr

### Start

To start clone this repository.

Afterwards change configuration connection settings in file `app/config/database.php` with your database settings

Next change configuration in `app/config/mail.php` to your mail provider.

To setup migrations

	php artisan migrate:install

To migrate DB Schema and seeds

	php artisan migrate --seed

Enjoy!

Demo app is at [Fortrabbit](http://habr.eu1.frbit.net/)
Russian tutorial article at [Habrahabr.ru](http://habrahabr.ru/post/197454/)
