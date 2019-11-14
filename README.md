# OS2Web

This is a Drupal 8 basic installation profile for an OS2Web project.

## Usage

### Composer

Use [drupal-composer project](https://github.com/drupal-composer/drupal-project) to fetch drupal core and os2web profile with contribution modules and their dependencies.

Example:
```
composer create-project drupal-composer/drupal-project:8.x-dev os2web --no-interaction
cd os2web
composer require os2web/os2web
drush si os2web --db-url=mysql://db_user:db_pass@mysql_host/db_name --account-pass=admin -y
```

### Installation profile

The installation profile only enables commonly used ui modules. It is up to the developer to decide which of the supplied OS2Web modules are needed. These can be enabled from the "Modules" page, otherwise they can be removed.
