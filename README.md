# get composer installer
$ curl -s https://getcomposer.org/installer | php

# Then proceed to install
$ php composer.phar update

# configure app/config/parameter.yml for your DB credentials

# Before using the project, load fixtures
$ php app/console doctrine:fixtures:load

# Now you can go to
rootpath/car or rootpath/mechanicalpart
