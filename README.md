# Laravel POS – REST API Backend

Backend ini adalah sistem Point of Sale (POS) berbasis **Laravel** dengan arsitektur **REST API** untuk digunakan pada aplikasi mobile atau web POS.  
Fitur meliputi manajemen produk, inventory, supplier, transaksi penjualan.
## 🔰 Badges
<p align="left">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue" />
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green" />
  <img src="https://img.shields.io/badge/Backend-Laravel%2010-red" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
  <img src="https://img.shields.io/github/stars/your-username/your-repo?style=social" />
</p>

---
## 🔧 Tech Stack

- **Laravel 10+**
- **PHP 8.1+**
- **Postgresql**
- **Laravel Sanctum (Authentication)**
- **2FA Google Authenticator**
- **REST API JSON**
- **Laravel Eloquent ORM**

---

## Installation

### Requirements

For system requirements you [Check Laravel Requirement](https://laravel.com/docs/10.x/deployment#server-requirements)

### Clone the repository from github.

```bash
https://github.com/iyamif/Pos-System-Backend-Laravel.git
```

The command installs the project in a directory named `YourDirectoryName`. You can choose a different
directory name if you want.

### Install dependencies

Laravel utilizes [Composer](https://getcomposer.org/) to manage its dependencies. So, before using Laravel, make sure you have Composer installed on your machine.

    composer install

### Setup Environment

```bash
cp .env.example .env
php artisan key:generate
```

### Database Migration

```bash
php artisan migrate --seed
```
this will initialize settings and create and admin user for you [email:kasir@pos.com - password: password123]

### Run Server

```bash
php artisan serve
```
Visit `localhost:8000` in your browser.



