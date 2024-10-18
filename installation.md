# Installation Guide

## Prerequisites

- **Laravel >= 10**
- **PHP**: Ensure PHP is installed (version 7.3 or higher).
- **Composer**: Install [Composer](https://getcomposer.org).
- **Node.js**: Install [Node.js](https://nodejs.org).
- **Database of your choice, default is sqlite**

## Installation Steps

1. **Install App:**
    ```bash
    composer create-project flightsadmin/loadcontrol
    ```
This will install package from [![Latest Version on Packagist](https://img.shields.io/packagist/v/flightsadmin/loadcontrol.svg?style=flat-square)](https://packagist.org/packages/flightsadmin/loadcontrol) and complete all settings

2. **Configure `.env`** with database credentials, app URL, etc.

3. **Run database migrations**:
    ```bash
    php artisan migrate --seed
    ```

4. **Start the application**:
    ```bash
    php artisan serve
    ```

5. **Default Login**
   ```bash
    Username: `test@example.com`
    Password: `password`
   ```

If you're deploying to a server, you will need to configure a web server like Nginx or Apache to serve the Laravel application.
