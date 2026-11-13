# Symfony starter

A minimal Symfony app in PHP from the official skeleton, with one controller and no database or templates.

- `src/Controller/HomeController.php`: the `/` route
- `src/Kernel.php`: the application kernel
- `config/`: bundles, packages and routes
- `public/index.php`: the front controller

## Run

```sh
composer install
php -S localhost:8000 -t public
```

Then open http://localhost:8000.
