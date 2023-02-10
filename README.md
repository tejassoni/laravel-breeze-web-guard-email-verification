# laravel-breeze-web-guard-email-verification
Laravel  Breeze Multi-Auth using Web guard


Server Requirements
=====================================
PHP Version => 7.4
Laravel Version => 8
MySQl => 5.7+

Setup Basic Commands
=====================================
1) git clone repository_url
2) cd laravel-breeze-multi-auth
3) composer update
4) configure .env database connection
5) php artisan serve

User Auth Routes Details
=====================================
1) User Login : http://127.0.0.1:8000/login
2) User Register : http://127.0.0.1:8000/register

User Credentials Details
=====================================
Username : user@user.com
Password : password

Admin Auth Routes Details
=====================================
1) Admin Login : http://127.0.0.1:8000/admin/login
2) Admin Register : http://127.0.0.1:8000/admin/register

Admin Credentials Details
=====================================
Username : admin@admin.com
Password : password

Project Requirement 
=====================================
1) Authentication Using Laravel Web Gaurd : 
2) User login
 -> email :
 -> password :
 -> after login it will redirect to specific user dashboard
3) User Register
 -> name :
 -> email :
 -> password :
 -> confirm password :
 -> after register it will redirect to specific user dashboard and auto login
4) User Roles Middleware Authentication

References Used To Develop : 
=====================================
a) https://www.youtube.com/watch?v=yXjHYTFRTC8
