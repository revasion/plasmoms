plasmoms
===
Pasmoms Management System

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist revasion/plasmoms "*"
```

or add

```
"revasion/plasmoms": "*"
```

to the require section of your `composer.json` file.

Configuration
-----

1) In your config/web.php

 'modules' => [
        ...
    'plasmoms' => [
            'class' => 'revasion\plasmoms\Plasmoms',
        ],
        ....
  ]

Usage
-----

Once the extension is installed, simply use it in your code by  :

```php


