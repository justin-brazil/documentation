+++
date = "2016-08-02T16:31:19+02:00"
title = "PHP"
toc = true
weight = 15

+++

PHP based application on the UTN infrastructure are served using `php-fpm` and
[NGINX](/server_software/nginx). Currently all new deployments are done using
PHP 7.2.

So far, no special settings have been set for the PHP installation, should this
be necessary, the PHP settings are available in `/etc/php/7.2/fpm/php.ini`.

### Useful commands
The commands you should keep in mind when working with NGINX are the following:

- `systemctl restart php7.2-fpm`, to restart the PHP7.2 deamon.
