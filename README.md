Yii 3 development environment
=============================

This repo contains tools to set up a development environment for Yii 3 packages.

It allows to work on separate packages and test the result in other packages at the same time.


Requirements
------------

- This is currently only tested on GNU/Linux and Windows with bash, if you have another system, please try and report if something is not working.
- PHP 7.1 or higher
- [Composer](https://getcomposer.org/) installed and
  available [as `composer` on the command line](https://getcomposer.org/doc/00-intro.md#globally)

Install
-------

    git clone https://github.com/yiisoft/yii-dev
    cd yii-dev
    ./yii-dev install
    
The above command will install all Yii 3 packages and run `composer install` in them.
You may select packages by providing a second argument:

    ./yii-dev install yiisoft/core
    ./yii-dev install yiisoft/db
    ...

Usage
-----

TBD

### Docker

Start a shell in a container

    docker-compose run --rm php bash

Afterwards you can run the above commands like `yii-dev install`.
