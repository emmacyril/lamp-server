# Simple LAMP Server Setup with Docker

## Description
Start developing a fresh php application with `docker` using `docker-compose`.

The images used in this repo is `php:8.1.1-apache` and `mysql:latest`. The goal is to make setting up the development as simple as possible.

IMPORTANT: this repo's purpose is mainly is to speedup your docker development environment for php projects. You're encouraged to replicate the setup on a more recent version toolings.

## Up and running
Clone the repo:
```
$ git clone https://github.com/emmacyril/lamp-server.git
$ cd lamp-server
```

Build the images and start the services:
```
docker-compose build
docker-compose up -d
```
### db
Running `./db` connects to your database container using mysql client.
```
$ ./db
mysql>
```
