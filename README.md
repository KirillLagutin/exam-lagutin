<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Экзамен по PHP - Laravel (CRUD, SQLite, Laravel Breeze, Tailwind CSS)

### Простенький CRUD на примере постов
    * Sqllite - в качестве бд
    * Laravel Breeze - для функционала аутентификации
    * Tailwind CSS - вместо бутстрапа

### Инструкция по запуску

#### Создаём в корне .env, копируем в него всё из файла env.example и в поле DB_CONNECTION=mysql меняем на DB_CONNECTION=sqlite

  ### В терминале, из папки проекта, прописываем команды: 
  
      composer update
      php artisan key:generate
      php artisan serve

  ### Для входа можно зарегистрироваться или использовать тестовую учётку:

      qqq@mail.ru
      qqqqqqqq
