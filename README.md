# Laravel 10 - Mini Projet QCM.

## Screenshots

![preview img](/preview.png)
![preview img](/preview2.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/FatimaEz-zahraaAIT-HSSAIN/Laravel-QCM.git project-name
```

Go to the project directory

```bash
  cd project-name
```

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer update
```

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Login

-   email = admin@example.com
-   password = 123
