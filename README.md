<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# RescueFood

**RescueFood** is a web application dedicated to food recovery and redistribution. This platform simplifies the collection of surplus food from restaurants and retailers, redistributing it to charitable associations and organizations. The application also provides recommendations to avoid food waste, as well as tools for tracking inventory and the needs of beneficiaries to optimize the solidarity chain.

## Features

- Collect and redistribute surplus food from restaurants and retailers.
- Provide recommendations to minimize food waste.
- Track inventory and beneficiary needs.
- Optimize food redistribution processes for charities.

## Technologies Used

- **Backend**: Laravel (PHP Framework)
- **Database**: MySQL
- **Frontend**: Blade templates (integrated with Laravel)

## Prerequisites

Before you start, ensure you have the following installed:

- **PHP** (version 8.1 or higher)
- **Composer** (Dependency Manager for PHP)
- **MySQL** (or any compatible database)
- **Node.js** and **npm** (for frontend assets and JavaScript dependencies)
- **Git** (for version control)

## Installation

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/NidhalNar/RescueFood.git

Navigate to the Project Directory:
cd RescueFood

Install Dependencies:
Use Composer to install the PHP dependencies:
composer install

Use npm to install JavaScript dependencies:
npm install
Setup Environment Variables:

Create a .env file by copying the example provided:
cp .env.example .env

Update the .env file with your database credentials and other configuration options:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password

Generate Application Key:
Laravel requires an application key to be set. Generate this key with:
php artisan key:generate

Run Migrations:
Set up the database structure by running the migrations:
php artisan migrate

Start the Development Server:
To start the Laravel development server, run:
php artisan serve
