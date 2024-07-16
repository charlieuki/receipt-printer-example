# Laravel Receipt Printer Example

## Overview

This is a Laravel web app serving as an example to use the [Laravel Receipt Printer package](https://github.com/charlieuki/receipt-printer).

I have tested this app successfully in the following environment:
- macOS 14.5 (Sonoma)
- PHP 8
- Laravel 10
- Epson TM-T82 receipt printer, connected via USB

## Usage

Follow these steps:

1. Clone this repository into a directory on your local computer
2. Open Terminal (macOS, Linux) or Git Bash (Windows)
3. Use `cd` command to change directory into the cloned repository
4. Use `composer install` command to install the dependencies
5. Use `php artisan serve` command to run PHP built-in server
6. Make sure that a receipt printer has been connected to your computer
7. Change the config inside `config/receiptprinter.php` according to your own environment, e.g the `connector_descriptor` should be your printer name
8. Open your web browser and point to: `http://127.0.0.1/print/test`
9. A sample receipt should be printed on your receipt printer

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
