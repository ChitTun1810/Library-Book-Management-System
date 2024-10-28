

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/ChitTun1810/Library-Book-Management-System
cd Library-Book-Management-System
```

### 2. Install Dependencies

Install the PHP dependencies:

```bash
composer install
```

### 3. Set Up Environment Variables

Create a `.env` file by copying `.env.example`:

```bash
cp .env.example .env
```

### 4. Generate Application Key

```bash
php artisan key:generate
```

### 5. Run Migrations and Seed the Database

Run the database migrations:

```bash
php artisan migrate:fresh
```

### 6. Serve the Application Locally

```bash
php artisan serve
```

