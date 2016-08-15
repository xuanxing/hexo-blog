---
title: PHP Composer
date: 2016-08-15 10:37:27
categories:
tags:
---

## Setup
``` shell
# current path is ~
pwd

# download composer.phar via php
php -r "readfile('https://getcomposer.org/installer');" | php

# global config
sudo -s
mv composer.phar /usr/local/bin/composer

# generate the "vendor" folder
composer install

# append composer vendor to environment variable
export PATH="~/.composer/vendor/bin:$PATH"
echo $PATH

# done!
```

<!--more-->

## Go on
``` shell
# download Laravel 5.0 via composer
composer global require "laravel/installer=~1.1" 
```
[Laravel 5.0](http://www.golaravel.com/laravel/docs/5.0/)

## Everything Else
[http://www.phpcomposer.com/](http://www.phpcomposer.com/)