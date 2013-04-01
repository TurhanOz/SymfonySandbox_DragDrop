# Install process

## clone this repo

## get composer installer
$ curl -s https://getcomposer.org/installer | php

## Then proceed to install
$ php composer.phar update

## configure app/config/parameter.yml for your DB credentials

## Before launching the project, load fixtures
$ php app/console doctrine:fixtures:load

## Now, from your browser, you can go to
rootpath/car or rootpath/mechanicalpart
