<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## UP Project

 run command `composer install`
 
 we have to install the laravel-echo-server package globally `npm install -g laravel-echo-server`
 
 run command `npm i`
 
 `set to .env file BROADCAST_DRIVER=redis and QUEUE_DRIVER=redis`
 
 run command `laravel-echo-server start`
 
 run command `php artisan serve`
 
 run command `php artisan queue:listen --tries=1`
 
 [test-broadcast](http://127.0.0.1:8000/test-broadcast)
 
 [test-private-broadcast](http://127.0.0.1:8000/test-private-broadcast)

## Requirements
- laravel 5.6
- npm
- composer
- redis
- sqlite

