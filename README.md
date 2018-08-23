# wordpress-lamp

Automated docker image to build a __LAMP environment for Wordpress__. 

Use this image to migrate your current server-meshed site to a slim dockerized 
environment.

It includes a _docker-compose.yml_ ready-to-run with MariaDB:

    wget https://raw.githubusercontent.com/rafacouto/docker-wordpress-lamp/master/docker-compose.yml
    docker-compose up -d

Once the containers were running, put a fresh wordpress in the ```www```
directory and browse the IP given to the PHP container.

Remember to review \*.env files provided with your appropiated environment.

Based on the official images: php and wordpress.

Issue box: https://github.com/rafacouto/docker-wordpress-lamp/issues

