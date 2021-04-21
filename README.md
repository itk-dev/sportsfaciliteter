# Sports-facilities proposal system

## Project setup

Run the docker container

`docker-compose up -d`

Install required packages

`docker-compose composer install`

Import drupal configuration

`docker-compose vendor/bin/drush config-import`

Export drupal configuration

`docker-compose vendor/bin/drush config-export`

## Sub theme

Sub-theme located in:

web/themes/sportsfaciliteter
