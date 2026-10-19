# Laravel Backpack User Administration

Laravel 12 administration project using Backpack CRUD and Spatie permissions.

## Overview

- Backpack user CRUD controller
- User request validation
- Admin middleware and permission configuration

## Stack

PHP 8.2+, Laravel 12, Composer, Blade, and Vite.

## Run locally

```bash
git clone https://github.com/AbdulSamadAhsan/LaravelAdminCrudBack.git
cd LaravelAdminCrudBack
composer install
npm install
```

Copy `.env.example` to `.env` and configure a local database, mail, and any external services required by the features you use.

```bash
php artisan key:generate
php artisan migrate
npm run build
php artisan serve
```

Run migrations only against your local development database. For asset development, run `npm run dev` in a second terminal.

## Project structure

- `app/` — application models, controllers, and supporting logic.
- `routes/` — web and API route definitions.
- `database/` — migrations and seeders.
- `resources/` — views and frontend assets.
- `tests/` — automated test sources.

## Checks

Use `php artisan test` for the existing PHP tests and `npm run build` to compile frontend assets. These commands were not run as part of this documentation update.

## Author

[Syed Abdul Samad Ahsan](https://github.com/AbdulSamadAhsan)
