# Laravel-5.4-Student-Management-System
For creating Laravel Project, you need to have following things.

    PHP >= 5.6.4
    OpenSSL PHP Extension
    PDO PHP Extension
    Mbstring PHP Extension
    Tokenizer PHP Extension
    XML PHP Extension
    Composer

#How to install

    1. composer install --no-scripts
    2. composer dump-autoload
    3. composer update
    4. copy .env.example .env
    5. php artisan key:generate
    6. php artisan config:clear
    7. php artisan migrate
    8. php artisan db:seed
    9. php artisan db:seed --class=RolesTablesSeeder
    10. php artisan db:seed --class=UsersTablesSeeder

How to use
    1. username: user
    2. password: 123
