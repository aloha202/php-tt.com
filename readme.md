Install the package

```composer require aradziuk/php-tt```

Set up executable

```touch testrunner.php```


In your runner

```php
<?php

require __DIR__.'/vendor/autoload.php';

$tt = new \Aradziuk\PhpTT\Tt();

$tt->run(
    __DIR__ . '/app', //dir with your classes
);
```
Test cases
