# Installation Guide

## Prerequisites
- **PHP >= 8.0**
- **Composer**
- **Laravel >= 10**
- **MySQL or PostgreSQL** database
- **Node.js & npm** for frontend assets

## Installation Steps

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
