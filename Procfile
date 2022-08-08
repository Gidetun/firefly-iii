web: touch /app/storage/database/database.sqlite
web: cd /app/storage/database
web: php artisan migrate --seed
web: php artisan firefly-iii:upgrade-database

web: vendor/bin/heroku-php-nginx -C nginx_app.conf public/
