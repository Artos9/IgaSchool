# IgaSchool

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![StyleCI](https://styleci.io/repos/43971660/shield?branch=master)](https://styleci.io/repos/43971660)

## TechStack
PHP 7.4

Laravel 7.x

## Install

Installation guide of Composer and MySQL praparation

### Download project

Download source code of master branch

```bash
    git clone https://github.com/Artos9/IgaSchool.git
```
Make a copy `.env.example` and rename to `.env`

Install the composer dependencies

```bash
composer install
```

Finally make sure you have a database named `IgaSchool`, and run the migrations and seeds

```bash
php artisan migrate --seed
```

### Production view

Project use `npm` package manager. 
Install `npm`
```bash
    sudo apt-get install npm
```
or use instructions on website  https://www.npmjs.com/get-npm

Genarate production view
```bash
    npm run production
```

### Usage

Laravel serve project.

```bash
    php artivan serve
```

### Features

### License

IgaShool project and The Laravel framework are open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)