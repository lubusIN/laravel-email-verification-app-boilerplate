
 **Laravel app boilerplate with email verification on registration**

Every time we at [LUBUS](http://www.lubus.in) start a laravel project , we need to re-implement this process of adding email verification in the project every time , so created this boilerplate out of personal needs 

How we achieved this can be read [here at our blog](http://www.lubus.in/blog/adding-email-verification-in-laravel-5-3-app-149)

> **The default master branch is for Laravel 5.4 , for Laravel 5.3 boilerplate switch to the v5.3 branch**

## Installation

 - Clone the repo using `git clone https://github.com/lubusIN/laravel-email-verification-app-boilerplate.git myApp`
 - `cd myApp`
 - Run `composer install`
 - If you already have a fresh install of laravel 5.3 , make sure to run `php artisan make:auth` at the start
 - Create the `.env` file from `.env.example` file & configure the following: App key, Database credentials, Mail driver
 - Run `php artisan key:generate`
 - Run `php artisan migrate`
 - That's it , you are done!

We advise you to read the blog mentioned above to understand what's going on here exactly. If you have any questions or suggestions , drop a comment on the blog or create an issue here , would be happy to help , or just come say hi :-) 

## About LUBUS

[LUBUS](https://lubus.in) is a web design agency based in Mumbai, India.
