
<p align="center">
<img src="https://cloud.githubusercontent.com/assets/5635513/21983354/2fba62e2-dc34-11e6-843c-fc6d3dc683ea.png" />
</p>

<p align="center">
<a href="https://packagist.org/packages/laradash/laravel-dashboard-api"><img src="https://poser.pugx.org/laradash/laravel-dashboard-api/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laradash/laravel-dashboard-api"><img src="https://poser.pugx.org/laradash/laravel-dashboard-api/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laradash/laravel-dashboard-api"><img src="https://poser.pugx.org/laradash/laravel-dashboard-api/license.svg" alt="License"></a>
</p>

## Introduction
Laradash is a mobile dashboard application which provides a light, fast and simple interface. 

You do not have to access a web-based dashboard by opening Chrome or Safari every time. you do not even have to directly develop the administrator page dashboard. 

Using Laradash, you can monitor your Laravel web application whenever and wherever. 

And this package helps to connect Laradash and web application built with the Laravel PHP framework easily.

## Installation
You can use [composer](https://getcomposer.org) to install this package.

```php
composer require laradash/laravel-dashboard-api
```
Add the LaradashServiceProvider to the end of the array in `app/config/app.php`.

```php
'providers' => [
  ...,
  Laradash\Laravel\LaradashServiceProvider::class
]
```

### Way to generate an API key
This package provides two method for generating keys.

1. Single API key (.env)
2. Multiple API keys (using database migration)


## Usage example
- Monitor the state of the server and API.
- Monitor service visitors
