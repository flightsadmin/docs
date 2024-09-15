# Installation Guide

## Prerequisites

- **Laravel >= 10**
- **PHP**: Ensure PHP is installed (version 7.3 or higher).
- **Composer**: Install [Composer](https://getcomposer.org).
- **Node.js**: Install [Node.js](https://nodejs.org).
- **Database of your choice, default is sqlite**

## Installation Steps

### Option 1 (Automatic)

    composer create-project flightsadmin/loadcontrol

This will install package from [![Latest Version on Packagist](https://img.shields.io/packagist/v/flightsadmin/loadcontrol.svg?style=flat-square)](https://packagist.org/packages/flightsadmin/loadcontrol) and complete all settings

### Option 2 (Manual)

1. **Clone the repository**:
    ```bash
    git clone https://github.com/flightsadmin/wab.git
    cd wab
    ```

2. **Install dependencies**:
    ```bash
    composer install
    npm install && npm run build
    ```

3. **Set up environment configuration**:
    ```bash
    cp .env.example .env
    ```

4. **Configure `.env`** with database credentials, app URL, etc.

5. **Run database migrations**:
    ```bash
    php artisan migrate --seed
    ```

6. **Start the application**:
    ```bash
    php artisan serve
    ```

7. **Default Login**
   ```bash
    Username: `test@example.com`
    Password: `password`
   ```

If you're deploying to a server, you will need to configure a web server like Nginx or Apache to serve the Laravel application.
