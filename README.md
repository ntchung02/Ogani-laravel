# OganiFood

## Run Locally

Clone the project

```bash
  git clone https://github.com/ntchung02/laravel-sell-food-web.git
```

Go to the project directory

```bash
  cd project-name
```

-   edit .env and database 

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```
```bash
    php artisan start serve
```
#### Login admin

-   email = admin@example.com
-   password = 123
