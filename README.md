# RabbitMQ CodeIgniter Library
A RabbitMQ wrapper for CodeIgniter.

## Dependencies
- RabbitMQ server version 3.5.5+
- CodeIgniter 3+
- [php-amqplib](https://github.com/videlalvaro/php-amqplib)

## Installing RabbitMQ
You can see full documentation for installing RabbitMQ server from the [official website](https://www.rabbitmq.com/download.html). 

## Installing RabbitMQ CodeIgniter Library
 - Copy file config/config.php into your CodeIgniter project's config directory. Edit config.php and replace access information based on your host configuration.
 - Copy file libraries/queue.php into your CodeIgniter project's libraries directory
 - Copy all files in third_party folder into your CodeIgniter project's third_party directory

## Current Features
- AMQP Connection
- Push functionality
