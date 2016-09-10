# Get8 PHP CodeSniffer Coding Standard

This is a custom coding standard, which is used by all Get8's projects.

## Installation

### Composer

This standard can be installed with the [Composer](https://getcomposer.org/) dependency manager.

1. [Install Composer](https://getcomposer.org/doc/00-intro.md)

2. Install the coding standard as a dependency of your project

        composer require --dev slowprog/get8-coding-standard:~1.0

3. Add the coding standard to the PHP_CodeSniffer install path

        vendor/bin/phpcs --config-set installed_paths vendor/slowprog/get8-coding-standard

4. Check the installed coding standards for "Symfony2"

        vendor/bin/phpcs -i

5. Done!

        vendor/bin/phpcs /path/to/code

### Stand-alone

1. Install [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)

2. Checkout this repository 

        git clone git://github.com/slowprog/get8-coding-standard.git

3. Add the coding standard to the PHP_CodeSniffer install path

        phpcs --config-set installed_paths /path/to/get8-coding-standard

   Or copy/symlink this repository's "Symfony2"-folder inside the phpcs `Standards` directory

4. Check the installed coding standards for "Symfony2"

        phpcs -i

5. Done!

        phpcs /path/to/code
