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

Routes Lists
=====================================
<ol>
  <li> Auth Routes </li>
  <ul>
    <li>User Login : http://127.0.0.1:8000/login </li>
    <li>User Register : http://127.0.0.1:8000/register </li>
    <li>Admin Login : http://127.0.0.1:8000/admin/login </li>
    <li>Admin Register : http://127.0.0.1:8000/admin/register </li>
  </ul>
</ol>

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
<ol>
  <li> Authentication Using Laravel Web Gaurd : </li>
  <li>Admin Role Routes </li>
    <ul>
      <li> <b> Registration Fields </b> </li>
      <li> Name : [ Validation Rules : Accept only strings and space, Required ] </li>
      <li> Email : [ Validation Rules : Accept only valid email address, Required ] </li>
      <li> Password : [ Validation Rules : Accept only valid password min 8 lenght with alphanumeric, Required ] </li>
      <li> Confirm Password : [ Validation Rules : should be same as Password field, Required ] </li>
      <li> Registration after registration share email verification link </li>
      <li> use migrations and make 5 dummy for Admin role using seeder </li>
      <li> follow laravel codeing standards </li>
      <li> seprate dashboard, table and model </li>
    </ul>
  <li>User Role Routes</li>
      <ul>
        <li> user/login and user/registrations after registration share email verification link </li>
        <li>use migrations and make 5 dummy for User role using seeder</li>
        <li>follow laravel codeing standards </li>
        <li>seprate dashboard, table and model </li>
      </ul>
</ol>
  
References : 
=====================================
a) https://www.youtube.com/watch?v=yXjHYTFRTC8
