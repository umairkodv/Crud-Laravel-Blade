# Laravel CRUD: Blade Breeze Version

This project is a simple Laravel CRUD for Tasks model built on top of Laravel Breeze starter kit Blade version.

![](https://laraveldaily.com/uploads/2024/12/crud-breeze-tasks.png)

---

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/umairkodv/Crud-Laravel-Blade.git
   cd project
   ```

2. Install dependencies:
   ```bash
   composer install
   npm install && npm run build
   ```

3. Copy the `.env` file and configure your environment variables:
   ```bash
   cp .env.example .env
   ```

4. Generate the application key:
   ```bash
   php artisan key:generate
   ```

5. Set up the database:
    - Update `.env` with your database credentials.
    - Run migrations and seed the database, repo includes fake tasks:
      ```bash
      php artisan migrate --seed
      ```

6. If you use Laravel Herd/Valet, access the application at `http://project.test`.

7. Log in with credentials: `test@example.com` and `password`.  

---

## Found a bug? Got a question/idea? 

Raise a GitHub issue. 
