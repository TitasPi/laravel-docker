# WEB dev Challenge 2025 - B Module
## PHP + Laravel + MariaDB + PhpMyAdmin Docker Template

Welcome to the **Dev Challenge 2025**! Follow the steps below to set up your repository and deploy your project successfully.

## 🚀 Getting Started

### Fork the Repository
You need to fork the official repository before making any changes. Follow these steps:

1. Click the **Fork** button in the top-right corner of this repository.
2. Name your repository in the following format:
   ```
   module-b-laravel-mariadb-{your-number}
   ```
   Example: `module-b-laravel-mariadb-1`
3. Click **Create Fork**.

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To run docker

### For first time only !
- `git clone https://github.com/refactorian/laravel-docker.git`
- `cd laravel-docker`
- `docker compose up -d --build`
- `docker compose exec php bash`
- `composer setup`

### From the second time onwards
- `docker compose up -d`

# Notes

### Laravel Versions
- [Laravel 11.x](https://github.com/refactorian/laravel-docker/tree/main)
- [Laravel 10.x](https://github.com/refactorian/laravel-docker/tree/laravel_10x)

### Laravel App
- URL: http://localhost:8000

### Mailpit
- URL: http://localhost:8025

### phpMyAdmin
- URL: http://localhost:8080
- Server: `db`
- Username: `dev2025`
- Password: `password`
- Database: `competition`


### Basic docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`

### Useful Laravel Commands
- Display basic information about your application
    - `php artisan about`
- Remove the configuration cache file
    - `php artisan config:clear`
- Flush the application cache
    - `php artisan cache:clear`
- Clear all cached events and listeners
    - `php artisan event:clear`
- Delete all of the jobs from the specified queue
    - `php artisan queue:clear`
- Remove the route cache file
    - `php artisan route:clear`
- Clear all compiled view files
    - `php artisan view:clear`
- Remove the compiled class file
    - `php artisan clear-compiled`
- Remove the cached bootstrap files
    - `php artisan optimize:clear`
- Delete the cached mutex files created by scheduler
    - `php artisan schedule:clear-cache`
- Flush expired password reset tokens
    - `php artisan auth:clear-resets`

### Laravel Pint (Code Style Fixer | PHP-CS-Fixer)
- Format all files
    - `vendor/bin/pint`
- Format specific files or directories
    - `vendor/bin/pint app/Models`
    - `vendor/bin/pint app/Models/User.php`
- Format all files with preview
    - `vendor/bin/pint -v`
- Format uncommitted changes according to Git
    - `vendor/bin/pint --dirty`
- Inspect all files
  - `vendor/bin/pint --test`

### Rector
- Dry Run
    - `vendor/bin/rector process --dry-run`
- Process
    - `vendor/bin/rector process`

## 🛠 Technologies list:
- **PHP** + **Laravel**
- **MoriaDB** + **PhpMyAdmin**
- **Docker** + **Docker Compose**


## 🎯 Competition Rules
- Do **not** change the repository structure.
- Ensure that your project builds and runs without errors.
- The final deployed version must be accessible via GitHub Pages.

Good luck and happy coding! 🚀

## 👨‍💻 Authors
- **[Martynas Kašelionis](https://github.com/martynasIN)** - Main contributor  

