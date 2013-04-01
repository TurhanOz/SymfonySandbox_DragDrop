# Install process

## clone this repo

## get composer installer
$ curl -s https://getcomposer.org/installer | php

## configure app/config/parameter.yml for your DB credentials

## Then proceed to install
$ php composer.phar update

## Before launching the project, load fixtures
$ php app/console doctrine:fixtures:load

## Now, from your browser, you can go to
rootpath/car or rootpath/mechanicalpart
