# Tiny crm

This is a small and Open-source CRM application created using the [Filament PHP](https://filamentphp.com/).

## Tech stack

- PHP (Laravel)
- Filament PHP
- Tailwind CSS
- Alpine JS
- PostgreSQL

## Live demo

The live demo of app is available [here](https://tiny-crm.frikishaan.com/).

## Local Installation

1. Clone the repository
2. Run the following commands - 
```bash
composer install #installing php dependencies

npm install # installing the JS dependencies

npm run build # to build the frontend assets
```
3. Replace the database credentials in the `.env` file.

```
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=tiny_crm
DB_USERNAME=postgres
DB_PASSWORD=password
```

4. Now run the following command to create the required tables in database -
```bash
php artisan migrate
```
Optionally, you can create the dummy data by running the seeder as - 
```bash
php artisan db:seed
```

## Need Consultancy? 
If you need help customizing this application or want to create your own application like this, contact me [here](https://www.upwork.com/services/product/consulting-hr-a-customer-crm-software-1651120102232907776?ref=project_share).
