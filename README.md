# Layout Master

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Layout Master is a Laravel package that provides [brief description of what your package does].

## Installation

You can install the package via composer:

```bash
composer require 7ts/layout-master
After installing the package, add the service provider to the providers array in the config/app.php file:

php
Copy code
'providers' => [
    // Other service providers...
    \SevenTS\LayoutMaster\LayoutServiceProvider::class,
],
Usage
After adding the service provider, you can customize your layout by publishing the required files based on your needs.

Publish Layout Views Only
To publish only the layout views, run:

bash
Copy code
php artisan vendor:publish --tag=views
Publish Controllers and Routes
If you want to include controllers and routes along with the layout views, run:

bash
Copy code
php artisan vendor:publish --tag=layouts
After publishing controllers and routes, add the additional service provider to the providers array in the config/app.php file:

php
Copy code
'providers' => [
    // Other service providers...
    \App\Providers\LayoutServiceProvider::class,
],
Contributing
If you would like to contribute to the project, please follow the steps below:

Fork the repository.
Create a new branch for your feature or bugfix.
Commit and push your changes.
Submit a pull request.
Security
If you discover any security-related issues, please email [your contact email] instead of using the issue tracker.

License
The MIT License (MIT). Please see License File for more information.
