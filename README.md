<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Installation

<li>laravel new Mcms</li>
<p>cd Mcms</p>

## Bootstrap
<li>composer require laravel/ui</li>
<li>php artisan ui bootstrap</li>
<li>php artisan ui bootstrap --auth</li>
<p>add this line to: resources\sass\app.scss</p>
@import '~bootstrap-icons/font/bootstrap-icons';
<li>npm install bootstrap@latest bootstrap-icons @popperjs/core --save-dev</li>
<li>npm install</li>
<li>npm run dev</li>

## twill


<p>latest version<p>
<li>composer require area17/twill</li>
configure env
<h3>install twill</h3>
<li>php artisan twill:install</li>
<i>your email and password</i>
<h2>conifure env</h2>




<div>
APP_URL=http://127.0.0.1:8000 <br>
ADMIN_APP_URL=127.0.0.1 <br>
ADMIN_APP_PATH=admin <br>
</div>


### databases

#### mysql
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=mcms
DB_USERNAME=root
DB_PASSWORD=
#### Sqlite
<div>
DB_CONNECTION=sqlite
DB_DATABASE=database.sqlite
DB_FOREIGN_KEYS=true
</div>

#### CMS Storage
<div>
MEDIA_LIBRARY_ENDPOINT_TYPE=local <br>
MEDIA_LIBRARY_IMAGE_SERVICE=A17\Twill\Services\MediaLibrary\Glide <br>
MEDIA_LIBRARY_LOCAL_PATH=uploads/ <br>
MEDIA_LIBRARY_CASCADE_DELETE=true <br>
FILE_LIBRARY_ENDPOINT_TYPE=local <br>
FILE_LIBRARY_LOCAL_PATH=uploads/ <br> 
</div>









