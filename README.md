# RabbitMQ CodeIgniter Library
A RabbitMQ wrapper library for CodeIgniter frameworks.
WARNING: Still in development

## Dependencies
- RabbitMQ server version 3.5.5
- CodeIgniter PHP Framework version 3.0.1
- [php-amqplib](https://github.com/videlalvaro/php-amqplib)

If you already installed RabbitMQ server in your host, you can skip "Installing RabbitMQ" step and proceed "Installing RabbitMQ CodeIgniter Library" step.

## Installing RabbitMQ
You can see full documentation for installing RabbitMQ server from [official website](https://www.rabbitmq.com/download.html). 

## Installing RabbitMQ CodeIgniter Library
 - Copy file config/config.php into your CodeIgniter project's config directory. Edit config.php and replace access information based on your host configuration.
 - Copy file libraries/queue.php into your CodeIgniter project's libraries directory
 - Copy all files in third_party folder into your CodeIgniter project's third_party directory

The library only have push method for now, i will update for other feature
