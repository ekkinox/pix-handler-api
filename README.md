# Pix Handler API

Backend API for the Pix Handler project.


### Installation

With composer:
```
$ composer install
```

### With build-in web server

You can run the api using symfony build-in server:
```
$ bin/console server:run 8000
```
Note: The api will be running on the port 8000.

### With docker

You can also run shipped docker php fpm container:
```
$ docker-compose up -d
```
Note: The api will be running on the port 8000.

## Tests

Run tests:
```
$ vendor/bin/phpunit
```