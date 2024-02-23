## Laravel Login Link

Link: https://github.com/spatie/laravel-login-link

### Install Breeze

Run this command

```
composer require laravel/breeze --dev
```

Config `.env`

```
DB_CONNECTION=sqlite
```

### Install Blade

Run the command

```
php artisan breeze:install blade
```

Migrate with

```
php artisan migrate
```

and run

```shell
npm run dev
```
