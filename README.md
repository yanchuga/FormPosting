# FormPosting
Its posting Form module for E-commerce Blog

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is simple Form posting module. You can check its Controller and Model to repeat a submit POST request on any form you have. 
	
## Technologies
Project is created with:
* Laravel: ^6.0
* MySQL: 8
* Node: 17.6
* NPM: 8.5
	
## Setup
To run this project:

```
$ clone the github repo
$ sudo apt install nodejs
$ run php artisan serve
$ create ENV file cp .env.example .env
$ get the website working on localhost
$ generae encryption key: php artisan key:generate
$ install mysql and create user
$ create an empty database
$ set the DB connection: port, url, user, pass in env file
$ make migration: php artisan migrate
$ run the app: php artisan serve

Now you get the main page with menu and FORM on Review item of menu
