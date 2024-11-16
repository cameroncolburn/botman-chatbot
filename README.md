## Installation Instructions

1. Clone repo to a local directory
2. In a terminal, change directory into the cloned directory
3. Run the command `composer install`
4. Run the command `cp .env.example .env`
5. Run the command `php artisan key:generate --ansi`
6. For local development, ensure you have a php/mysql implementation setup such as xampp
7. In phpmyadmin create a new database called 'botman'
8. Optional for local development, set a username and password
9. In the laravel project, open the .env file and ensure the database variables are setup, similar to the following:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=botman
DB_USERNAME=<YOUR DB USERNAME>
DB_PASSWORD=<YOUR DB PASSWORD>
``` 
10. In the terminal, run the following command `php artisan migrate`
4. Run the command `php artisan serve`
5. Open a browser and navigate to `127.0.0.1:8000`