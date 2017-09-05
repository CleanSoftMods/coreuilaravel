# CoreUI-laravel
This is a very crude port of the [CoreUI](https://github.com/mrholek/CoreUI-Free-Bootstrap-Admin-Template) bootstrap 4 template.

## Installation:
First clone or download this repository and cd to that directory.
Make sure you have bower, gulp and nmp installed on your system. Set the storage folder permissions to 777. After this run the following commands.
```
npm install --no-bin-links
bower install
composer install
gulp --production
cp .env.example .env
```

fill the .env file

```
php artisan key:generate
php artisan serve
```
## Usage:
Uncomment the auth middleware in the HomeController to enable the authentication check.


### Credits:
Big thanks to [CoreUI Bootstrap 4 Admin Template](https://github.com/mrholek/CoreUI-Free-Bootstrap-Admin-Template) for making such an awesome bootstrap template.
