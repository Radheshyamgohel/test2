

## About Laravel
Neonix888 is a web application for provide different type of server currently provide IP Sweep functionality.

## How To Setup && Installation Project
Requirements:
PHP version : > 7.2.* && < 8.0.*
DB: PhpMyAdmin

Clone the code into your local directory 

git clone https://github.com/developer-yii/neonix888.git

After clone process done goto clone directory and run following command into the terminal or cmd
composer install

Get .env from your developer and paste it on your project directory

Create database for this project name neonix888 and set db config into the .env file

once DB config setup done run the following command.

php artisan migrate

Run the seeder for creating default record into the database.

php artisan db:seed

It will create database table into your configer database

## How To Push Project

git add .
git commit -m "commit message"
git push origin master
