# Laravel POS – REST API Backend

Backend ini adalah sistem Point of Sale (POS) berbasis **Laravel** dengan arsitektur **REST API** untuk digunakan pada aplikasi mobile atau web POS.  
Fitur meliputi manajemen produk, inventory, supplier, transaksi penjualan.

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

### Config file

Rename or copy `.env.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file.

### Database

1. Migrate database table `php artisan migrate`
1. `php artisan db:seed`, this will initialize settings and create and admin user for you [email:kasir@pos.com - password: password123]

### 2. Setup Environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Database Migration

```bash
php artisan migrate --seed
```

### Run Server

1. `php artisan serve` 
1. Visit `localhost:8000` in your browser.

