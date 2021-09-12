# LAMP-Docker-Compose
LAMP+phpMyAdmin environment using Docker Compose

## What´s include:
libzip-dev

zlib1g-dev

curl

wget

p7zip-full

## How to create new Symfony Project
composer create-project symfony/framework-standard-edition . "2.8"

## Troubleshooting
### If you can't access to app_dev.php
Docker Compose set local IP to 172.20.0.1. Add to app/web/app_dev.php