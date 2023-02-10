# laravel-breeze-web-guard-email-verification
Laravel  Breeze Multi-Auth using Web guard


Server Requirements
=====================================
<ul>
  <li>PHP Version => 7.4</li>
  <li>Laravel Version => 8</li>
  <li>MySQl => 5.7+</li>
</ul>

Setup Basic Commands
=====================================
1) git clone repository_url
2) cd laravel-breeze-web-guard-email-verification
3) composer update
4) create database and configure .env database connection
5) php artisan migrate
6) php artisan db:seed
7) php artisan serve

Auth Routes Details
=====================================
1) User Login : http://127.0.0.1:8000/login
2) User Register : http://127.0.0.1:8000/register
3) Admin Login : http://127.0.0.1:8000/admin/login
4) Admin Register : http://127.0.0.1:8000/admin/register

Credentials Details
=====================================
<b>User Role</b>
<ul>
  <li>Username : user@user.com</li>
  <li>Password : password</li>
</ul>

<b>Admin Role</b>
<ul>
  <li>Username : admin@admin.com</li>
  <li>Password : password</li>
</ul>

Project Requirement 
=====================================
1) Authentication Using Laravel Web Gaurd : 
2) Admin Role Routes

References : 
=====================================
a) https://www.youtube.com/watch?v=yXjHYTFRTC8
