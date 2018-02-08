Files/folders:

    db/dump.sql

        database dump

    etc/nginx/default.conf

        nginx config

    www/public_html

        document root

    .env

        enviroment variables:

            BASE_PATH - root folder
            LIB_PATH - path to docker-compose.yml form https://github.com/fulmine29a/docker-dev-php-v1.git
            NGINX_IP = ip address for nginx

Install:

    set enviroment variables

Run:
    docker-compose up