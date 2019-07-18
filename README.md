INSTALL
-------------
```bash
docker-compose up -d
docker-compose exec php bash
cd /var/www/app
composer update
./yii migrate
```
