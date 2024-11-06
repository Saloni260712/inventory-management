# Inventory Management System (Laravel)

This is a basic **Inventory Management System** built using **Laravel**, featuring authentication, role-based access (Admin/User), and a responsive navbar with **Bootstrap 5**.

## Features
- User authentication (login, registration, logout)
- Role-based access (Admin, User)
- Inventory management (add, update, delete items)
- Responsive navbar with Bootstrap 5

## Prerequisites
- PHP (>= 7.4)
- Composer
- Laravel (via Composer)
- MySQL or SQLite
- Node.js and NPM

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/inventory-management.git
   cd inventory-management
   ```

2. **Install PHP Dependencies:**
   ```bash
   composer install
   ```

3. **Configure Environment:**
   Copy `.env.example` to `.env` and configure the database settings.

4. **Generate Application Key:**
   ```bash
   php artisan key:generate
   ```

5. **Run Migrations:**
   ```bash
   php artisan migrate
   ```

6. **Install Frontend Dependencies:**
   ```bash
   npm install
   ```

7. **Compile Frontend Assets:**
   ```bash
   npm run dev
   ```

8. **Start the Laravel Server:**
   ```bash
   php artisan serve
   ```

Your application will be available at [http://localhost:8000](http://localhost:8000).

## Usage
- **Login/Register:** Users can log in or register (default role: User).
- **Admin Access:** Admins can manage inventory (add, update, delete items).

## File Structure
- `app/Http/Controllers`: Controllers for authentication and inventory management.
- `resources/views`: Blade templates.
- `routes/web.php`: Routes configuration.


## License
MIT License.
