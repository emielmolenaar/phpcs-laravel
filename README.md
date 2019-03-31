
# Emiel Molenaar's PHPCS Configuration 

I use this package to set up a consistent PHPCS configuration across my Laravel projects. The ruleset is based on [@nandosalles' ruleset](https://medium.com/@nandosalles/the-ruleset-phpcs-for-my-laravel-projects-a54cb3c95b31).

If you wish to use this configuration in your project, install it using composer:

`composer require --dev emielmolenaar/phpcs-laravel` 

Afterwards, you may run `php vendor/bin/phpcs -i` and see `phpcs-laravel` listed as an installed ruleset.

You may now use the ruleset like so:

`php vendor/bin/phpcs --standard=phpcs-laravel my_file.php`

_Note_, If you're installing globally with Composer you can simply do `phpcs -i`.

Contributions welcome.
