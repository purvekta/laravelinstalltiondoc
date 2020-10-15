Laravel Coding Flow
for crud operations
first Create Database Migration file
then Models and controllers then Routes and last Blade files.
step 1 install new application from laravel

laravel new appname
 step 2: connect it withdatabase throguh .env file
 --------------------------------------------------------------------------------------------
 step3:for authenitcation for pacakge installation
step 1.composer require laravel/ui
then 
step 2
Using Boostratp :
php artisan ui bootstrap --auth

Using Vue:
php artisan ui vue --auth

Using React:
php artisan ui react --auth

php artisan make:auth
if css files are not loaded then copy folder css and js from public and paste it in public folder

step3: npn install and then npm run dev

if the tables are not created then run the migrations 
php artisan migrate
------------------------------------------------------------------------------
for create the table 
php artisan make:migration create_users_table

php artisan make:migration create_studentss_table --create=students

for fresh migration command: php artisan migrate:fresh

command for cahe clear
php artisan config:cache
php artisan storage:link
