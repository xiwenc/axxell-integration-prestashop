# axxell-client-php

## Requirements

PHP 5.4.0 and later

## Installation & Usage
### Composer

You can install the bindings via [Composer](http://getcomposer.org/). Add this to your `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/CINAQ/Axxell.git"
    }
  ],
  "require": {
    "CINAQ/Axxell": "*@dev"
  }
}
```

Then install via `composer install`

### Manual Installation

If you do not wish to use Composer, you can download the latest release. Then, to use the bindings, include the `autoload.php` file.
```php
    require_once('/path/to/axxell-client-php/autoload.php');
```

## Tests 

To run the unit tests:
```
composer install
./vendor/bin/phpunit lib/Tests
```

## Author




