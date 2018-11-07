## Требования к программному обеспечению серверной части 
### Минимальные требования
Для функционирования сайта необходимо следующее программное обеспечение:
*  ***Операционная система:*** Linux
* ***Веб сервер:*** Nginx 1.10+ или Apache 2.4+
* ***База данных:*** MySQL 5.6+ / Mariadb 10.1+ / SQLite 3.x
* ***PHP 7.1+***
* ***Место на диске:*** 500Mb+
* Настройки PHP:
  - register_globals off
  - safe_mode off
  - session.save_handler user
  - session.cache_limiter nocache
  - error_reporting E_ALL
  - php_memory_limit не менее 100мб, но лучше 500Mb+
  - The standard PHP extensions (enabled by default) Hash and JSON are required
  - PDO support
* План хостинга: память 128+мб
### Рекомендуемые требования
* ssh/sftp
* composer & memory 500Mb+
* drush 8+
* drupal-console
* node-js, gulp-cli
* git
* тип жесткого диска: ssd
