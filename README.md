# RabbitMQ Watch Project
This project aims at doing technology watch on RabbitMQ, configuration and manage async transport messenger in a Symfony project.

## Installation
For start the project, simply run the command `docker-compose up -d` at the root of the project.

Enter the rabbitmq_symfony container with command `docker exec -it rabbitmq_symfony bash;`.

Install the dependencies with composer install in container.

Run project on http://rabbitmq-watch.loc:8011

Always in container enter this command `sf messenger:consume -vv`

Get your mail test in mailcatcher on http://localhost:1080

