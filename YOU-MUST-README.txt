How to install this project?
1. Download or clone this project.
2. Create a database with any name
3. copy file _env.example and rename to .env, put there your local DB credentials, like username - root,
password - password , db-name - laravel
4. Open a terminal and type the following command:
- composer update
- composer install
- composer install --optimize-autoloader --no-dev
- npm update
- npm install
- php artisan key:generate
- php artisan optimize
- php artisan route:cache
- php artisan config:cache
- php artisan view:clear

- php artisan migrate
It will create your user, and you can enter to admin panel with urls
- php artisan user:create "test" "test@mail.com" "1234" --force

- php artisan serve
- npm run dev


NOTE: This project was created with:
- PHP version 8.1 (cli)
- Composer Version 2
- Node 16
- Laravel v9
