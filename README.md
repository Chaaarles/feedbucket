# Feedbucket

A simple tool to gather feedback from your peers.

## Install and run

Feedbucket is a Laravel application that uses Laravel Sail to run in a Docker container. To install and run the
application, follow these steps:


```shell
# Clone the repository
git clone <repository>
cd <repository>
```

```shell
# Install dependencies, generate key, run migrations and start the application
composer install
npm install
cp .env.example .env
php artisan key:generate
npm run dev
./vendor/bin/sail up -d
./vendor/bin/sail artisan migrate
./vendor/bin/sail artisan storage:link
```
