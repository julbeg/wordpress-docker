
# Wordpress Docker
A simple docker setup for Wordpress local development with :
- PHP 8.2
- Xdebug 3
- OPcache
- Mysql 8.0
- Phpmyadmin
- Mailpit

## Installation
- Rename the wordpress config file for local development

```bash
mv ./wordpress/wp-config-local.php ./wordpress/wp-config.php
```

- [Download](https://wordpress.org/download/) and copy your wordpress files into the `./wordpress` directory 

- Build and run

```bash
docker compose up -d --build
```

## Usage

- Go to [localhost](http://localhost) for wordpress
- Go to [localhost:8080](http://localhost:8080) for phpmyadmin
- Go to [localhost:8025](http://localhost:8025) for mailpit