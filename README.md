## How to start development

1. Install composer dependencies
```
composer install
npm install
```

2. Build frontend asset
```
npm run dev
```

3. Copy `.env.example` to `.env` and fill out the database credentials
```
cp .env .env.example
```

4. Run key generate, migrations and seeders
```
php artisan key:generate
php artisan migrate --seed
```

5. Run Laravel server
```
php artisan serve
```
You can access the project at `http://localhost:8000`

6. Run test cases
```
./vendor/bin/phpunit
```
## How to run test cases

```
./vendor/bin/phpunit
```
