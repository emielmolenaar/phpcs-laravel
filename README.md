
# Emiel Molenaar's PHPCS Configuration 

I use this package to set up a consistent PHPCS configuration across my Laravel projects. The ruleset is based on [@nandosalles' ruleset](https://medium.com/@nandosalles/the-ruleset-phpcs-for-my-laravel-projects-a54cb3c95b31).

If you wish to use this configuration in your project, install it using composer:

`composer require --dev emielmolenaar/phpcs-laravel` 

Afterwards, run `php vendor/bin/phpcs -i` to verify that `phpcs-laravel` is listed as an installed ruleset.

You may now use the ruleset like so:

`php vendor/bin/phpcs --standard=phpcs-laravel app/`

Contributions welcome.
