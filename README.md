# Docker image for testing Laravel applications with PHPUnit

Inspired by https://github.com/khoanguyen96/dockerfiles

## Running tests
Run the following command to run tests within the docker image:
```
docker run -v $(pwd):/app --rm 8bitz/php-laravel-composer:latest ./vendor/bin/phpunit --configuration phpunit.xml tests
```
