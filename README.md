# blog-front

## Install PHP

```
git clone https://github.com/WedgeSama/blog-front.git .
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migration:migrate
php bin/console hautelook:fixtures:load --purge-with-truncate
```

## Install Front
```
yarn
```
