<div align="center"> 
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmVjZzJpbG11aTgyeXVrcHZ6cW4wMGh4ZGRvdTcwdzF5YjE3OGhkYyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/DwOjs8b0gWK92629t3/giphy.gif"  />
</div>

## Project Setup & Dependencies

### Create a new Laravel project

```bash
composer create-project laravel/laravel project-name
cd project-name
```

### Install a package

```bash
composer require vendor/package-name
```

### Install dev dependencies

```bash
composer require --dev vendor/package-name
```

### Update dependencies

```bash
composer update
```

### Remove a package

```bash
composer remove vendor/package-name
```

## Artisan Commands

### Serve project locally

```bash
php artisan serve
```

### Generate a controller

```bash
php artisan make:controller ControllerName
```

### Generate a model

```bash
php artisan make:model ModelName
```

### Generate a migration

```bash
php artisan make:migration create_table_name_table
```

### Run migrations

```bash
php artisan migrate
```

### Rollback migrations

```bash
php artisan migrate:rollback
```

### Seed the database

```bash
php artisan db:seed
```

### Clear caches

```bash
php artisan cache:clear
php artisan config:clear
php artisan route:clear
php artisan view:clear
```

## Environment & Config

### Create `.env` from example

```bash
cp .env.example .env
php artisan key:generate
```

### Check Laravel version

```bash
php artisan --version
```

## Composer Shortcuts

### Check installed packages

```bash
composer show
```

### Autoload optimization

```bash
composer dump-autoload -o
```

### Global composer package install

```bash
composer global require vendor/package-name
```

## Tips

* Always run `composer install` after pulling a new project.
* Use `php artisan route:list` to see all routes.
* Keep `.env` secret; never commit it.
* Use `composer outdated` to see outdated packages.

