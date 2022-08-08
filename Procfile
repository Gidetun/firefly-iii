worker: sqlite3 /app/storage/database/database.sqlite
worker: php artisan migrate --seed
worker: php artisan firefly-iii:upgrade-database

web: vendor/bin/heroku-php-nginx -C nginx_app.conf public/
