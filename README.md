### Welcome to Practical Project 9

## Product name 

Laravel MVC CRUD Listings app.

## How to run project?

-   Download [XAMPP](https://www.apachefriends.org/index.html) and install it.
-   Download [MySQL Workbench](https://www.mysql.com/products/workbench/) and install it.
-   Download or clone git repository BIT_PP9 and place it inside htdocs directory (XAMPP).
-   Run XAMPP and start Apache and MySQL server.
- Open MySQL Workbench and create database.
- Open up your project and rename .env.example to .env
- Change database name in .env file to your created database name 
- Install composer (installation instructions: Composer) and in the terminal:
- if composer is installed locally in console type in: php 'path to composer.phar file'/composer.phar install
- if composer is installed on your system globally in console type in: composer install
- To run project in terminal type in these commands:

```sh
    php <path-to-composer.phar>/composer.phar install           Installs dependencies
    php artisan migrate                                         Creates all the nessesary tables and columns.
    php artisan db:seed                                         Adds the dummy data.
    php artisan key:generate                                    Generates app key in .env file
    php artisan serve                                           Runs live server.
```

-   Open your browser and in the searchbar type in:

```sh
http://127.0.0.1:8000/
```

-   Or press this link => [Localhost:8000](http://127.0.0.1:8000/)

## What technologies I used?

Laravel.
