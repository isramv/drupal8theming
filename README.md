# Docker for C3 Theming training.

## Requirements

- Docker CE
- docker-compose

 - Install a new D8 site with composer

```php
composer create-project drupal-composer/drupal-project:8.x-dev drupal --stability dev --no-interaction
```
## Edit hosts file.

```
$ sudo vim /etc/hosts
```

add the line: `127.0.0.1 drupal8theming.localhost` and save.

 -  Run composer
```
$ docker-compose up -d
```
