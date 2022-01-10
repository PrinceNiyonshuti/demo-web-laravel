# Demo Web


## Documentation

before starting to run the project


## Requirements

- create your .env file 
- create your database
- Xampp or apache server

## after run these script 

    composer install
    cp .env.example .env or copy .env.example .env
    php artisan key:generate
    php artisan migrate
    php artisan db:seed
    or
    php artisan migrate:fresh --seed

## Feedback and issues

Any issue and feedback from the app don't hesitate to make an issue
