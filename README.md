# Script runner

[![Software License][ico-license]](LICENSE.txt)

Class for running separate processes of PHP CLI scripts.

## Requirements

*   PHP >= 7.1

## Install

Use class as standalone:

```php
require 'ScriptRunner.php';
use PhpStrict\ScriptRunner\ScriptRunner;
```

Install with [Composer](http://getcomposer.org):
    
```bash
composer require php-strict/script-runner
```

## Usage

```php
use PhpStrict\ScriptRunner\ScriptRunner;

$sr = new ScriptRunner('script.php', 4);
$sr->run();
```

## Tests

To execute the test suite, you'll need [Codeception](https://codeception.com/).

```bash
vendor/bin/codecept run
```

[ico-license]: https://img.shields.io/badge/license-GPL-brightgreen.svg?style=flat-square