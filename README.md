Hostel
=====

Simple Hostel Management System

## Features 
* Manage students
* Manage rooms
* Manage rent payment
* Set payment rates
* View reports/receipts

## Roles
### 1.  Admin
Has access to all the features
### 2.  Student
Can book a room at a particular hostel


# Quick Guide

1. Clone this repo to your documents root e.g under `c:\xampp\htdocs\hosts` on linux or windows or `c:\wampp\www\hosts` on windows
2. Import the `dairy.sql` file to your database. (You can create a database called dairy using phpmyadmin and import this file into it)
3. open `inc\conn.incl.php` file and enter your database settings
```php
define('db_host', 'localhost');
define('db_user', 'root');
define('db_password', '');
define('db_database', 'hostel');
```
4. Open the url to your project e.g [http://localhost/hosts](http://localhost/hosts) and login with an already created account

## Demo Accounts
### 1. Admin
username: admin

password: shakes
### 2. Student
ID: 12345678

password: 12345678

 


