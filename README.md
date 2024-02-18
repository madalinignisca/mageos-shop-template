# Mage-OS dev shop

## Requirements

- PHP 8.1 / 8.2 / 8.3 with the extensions (if using debian with sury's repo) | Best to use 8.2 for the moment
    - php8.2-bcmath
    - php8.2-curl
    - php8.2-xml
    - php8.2-gd
    - php8.2-intl
    - php8.2-mbstring
    - php8.2-mysql
    - php8.2-soap
    - php8.2-xsl
    - php8.2-zip
- Docker for services | create a .env file with COMPOSE_PROJECT_NAME=your_project_name | add variables from docker-compose.yml to overide them
    - opensearch 2.5
    - mariadb 10.6
    - rabbitmq 3.11
    - redis 7.0