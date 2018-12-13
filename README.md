## intro
This is a migration tool such as `Laravel migration`, but sometime we just need only *migration feature* run as a application, and now you can use it anywhere.

## how to use
Just as some tools you have used , you can clone it and run `composer install` in your application.

What I have do is just included and packaged [Doctrine Migrations](https://github.com/doctrine/migrations) to let it work as a application , so , you can use that orders from the docs.

This order will list the help.
```
php migration
```
just like you use `./vendor/bin/doctrine-migrations` in `Doctrine Migrations`.

Others orders just like it.


## dependencies

- . [Doctrine Migrations](https://github.com/doctrine/migrations)
- . [symfony/dotenv](https://github.com/symfony/dotenv)
- . [jakub-onderka/php-console-highlighter](https://github.com/jakub-onderka/php-console-highlighter)