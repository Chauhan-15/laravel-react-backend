# dompixel-shop-assignment
product catalog crud operation

# Technologies
PHP (version 8.1)
Laravel Framework (version 10.15)

# Clone the repository
git clone https://github.com/Chauhan-15/laravel-react-backend.git

# Switch to the repo folder
cd laravel-react-backend

# Install all the dependencies using composer
composer install

# Copy the example env file and make the required configuration changes in the .env file
cp .env.example .env

# Generate a new application key
php artisan key:generate

# Run the database migrations (Set the database connection in .env before migrating)
php artisan migrate

# Start the local development server
php artisan serve
You can now access the server at http://localhost:8000

# command list
git clone https://github.com/Chauhan-15/laravel-react-backend.git
cd laravel-react-backend
composer install
cp .env.example .env
php artisan key:generate
Make sure you set the correct database connection information before running the migrations Environment variables
php artisan migrate
php artisan serve