# Motivational Inspiring (African)Quotes

##Installation
Include this package via Composer:
```console
composer require abdurrazaq/inspiring
```
### Laravel 5.3+

In Laravel 5.3, `app/Console/Commands/Inspire.php` has moved to `routes/console.php` clousure command.

Edit your `use` in the same way in Laravel 5.2 and backwards:

```php
<?php

//use Illuminate\Foundation\Inspiring;
use Abdurrazaq\Inspiring;

/*
|--------------------------------------------------------------------------
| Console Routes
|--------------------------------------------------------------------------
```

### Laravel 5.0 to 5.2

Edit your `app/Console/Commands/Inspire.php`

```php
<?php

namespace App\Console\Commands;

use Illuminate\Console\Command;
//use Illuminate\Foundation\Inspiring;
use Abdurrazaq\Inspiring;;
```

Then run `php artisan inspire` and be inspired! :)