release: sqlite3 /app/storage/database/database.sqlite
release: php artisan migrate --seed
release: php artisan firefly-iii:upgrade-database

web: vendor/bin/heroku-php-nginx -C nginx_app.conf public/
