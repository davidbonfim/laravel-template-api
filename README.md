## Template for Blockstairs API
#

This document was created at 09/09/2022 by Leandro Maia.


## Installation Guide

We are using [Laravel Sail](https://laravel.com/docs/9.x/sail) for our development environment.

To make Sail's command more easily you can add this alias to your shell configuration:

`alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'`

### Steps
 - Clone the project
 - Run the composer install (`composer install`)
 - Create a copy of the .env file (`cp .env.example .env`)
 - Run the containers using Sail (`sail up -d`)
 - Run the migrations (`sail artisan migrate`)
 - Create the APP KEY (`sail artisan key:generate`)

#



To use the Laravel telescope just type `/telescope` on the main address.

Telescope only run in development environment.

To run Horizon type `php artisan horizon`
If you want to check the dashboard just type `/horizon` on the main address.

Horizon only run in development environment.
