<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Install Project
 
 clone the project from github or download .zip `https://github.com/OlegMarko/laravel-echo-server-test.git`
 
 run command `composer install`
 
 we have to install the laravel-echo-server package globally `npm install -g laravel-echo-server`
 
 run command `npm i`
 
 make `.env` file like to `.env.example`

 run command `php artisan key:generate`
 
 `set to .env file BROADCAST_DRIVER=redis and QUEUE_DRIVER=redis`
 
 run command `laravel-echo-server start`
 
 run command `php artisan serve`
 
 run command `php artisan queue:listen --tries=1`
 
## Test Routes
 
 [test-broadcast](http://127.0.0.1:8000/test-broadcast)
 
 [test-private-broadcast](http://127.0.0.1:8000/test-private-broadcast)

## Requirements
- laravel 5.6
- npm
- composer
- redis
- sqlite

