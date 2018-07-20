Coder Review
============

This is a developer library that assists with code review so Backdrop code
can maintain standards defined on https://api.backdropcms.org

Built-in support for:
 - Backdrop Coding Standards - https://api.backdropcms.org/php-standards
 - Handle text in a secure fashion - https://api.backdropcms.org/securing-user-input

Installation
------------

User composer to install:

```bash
composer require backdrop/coder
```

Running phpcs Code Checks
-------------------------

```bash
./vendor/bin/phpcs --standard=./vendor/backdrop/coder/coder_sniffer/Backdrop path/to/code
```

Automated Testing (PHPUnit)
---------------------------

To execute the phpunit tests:

```bash
./vendor/bin/phpunit
```

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Current Maintainers
-------------------

- Geoff St. Pierre [serundeputy](https://github.com/serundeputy)

Credits
-------

Doug Green
douggreen@douggreenconsulting.com

Solotandem - https://www.drupal.org/u/solotandem
