Git Repo:
---------------------------------------------------------------
git clone https://github.com/prite-shh/start_smart_academy.git

System Requirement:
---------------------------------------------------------------
=> WAMP / XAMPP - PHP 8
=> Composer
=> PHP in system variables

Steps to Setup Project:
---------------------------------------------------------------
1. Command - composer install / composer update
2. Command - cp .env.example .env
3. Command - php artisan key:generate
4. Create Database in PhpMyAdmin
5. Enter Database details in ".env" file
6. Command - php artisan migrate
7. Command - php artisan storage:link
8. Command - php artisan DB:seed
9. Command - php artisan serve

---------------------------------------------------------------
Great !! You are good to go...
