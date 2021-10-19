<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. 

## Developer Docs

## Run This Project

## Install composer and xamp/wamp/laragon
## Open a Terminal or CMD or Bash on project folder.

```bash
composer install
```
 ## Start the local server

```bash
php artisan serve
```


## [Command For cleaning cache and dumps]
```bash
composer dump-autoload
```
```bash
php artisan optimize:clear
```


## Endpoint: /api/check_subject
data/parameters:{
    
    hsc_math [datatype: boolean(0/1), required],

    hsc_biology [datatype: boolean(0/1), required],

    math_score [datatype: numeric(0,1,2,3....), required],

    physics_score [datatype: numeric(0,1,2,3....), required],

    chemistry_score [datatype: numeric(0,1,2,3....), required],

    biology_score [datatype: numeric(0,1,2,3....), required]
}


