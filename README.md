The helpers box
===============================

[![Latest Stable Version](https://poser.pugx.org/bsadnu/helpers-box/v/stable)](https://packagist.org/packages/bsadnu/helpers-box) 
[![Total Downloads](https://poser.pugx.org/bsadnu/helpers-box/downloads)](https://packagist.org/packages/bsadnu/helpers-box) 
[![License](https://poser.pugx.org/bsadnu/helpers-box/license)](https://packagist.org/packages/bsadnu/helpers-box)

This library provides a number of static helper methods. At the moment it is a full copy of [Laravel 5.7 Arr and Str helpers](https://laravel.com/docs/5.7/helpers).

## Installation

Open a command console, enter your project directory and execute:

```console
$ composer require bsadnu/helpers-box
```

## Usage

Simply call static methods as follows:

```php
<?php

...

use Bsadnu\HBox\Arr;
use Bsadnu\HBox\Str;

...

class SomeClass
{
    ...
    
    public function someMethod()
    {
        ...
        
        Arr::pluck($someArray, $value);
        
        Str::camel($someString);
        
        ...
    }

    ...
}
```

