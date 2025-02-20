

```bash
composer install
bin/console doctrine:database:create
bin/console doctrine:migrations:migrate
symfony server:start -d
bin/console cache:clear --env=dev
```