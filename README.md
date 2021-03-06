# MYSQL DOCKERIZED WITH CLI
MySQL Dockererized with CLI to import and export databases.

The CLI is inspired by the [Dockerized Magento 2](https://github.com/arvatoSCM/dockerize-magento2) project.

## Usage
1. Download this project
2. Copy .env-example as .env and fill the variables
3. Run `sudo chmod +x bin/console` to give CLI permissions to run
4. Run `bin/console start`
5. Enjoy it

## Import databases
1. Copy into dumps folder your dump
2. Run `bin/console mysql:import dump_name database_name`
    - Important: for dump_name only type the name without .sql extension

## Create a dump
1. Run `bin/console mysql:dump database_name dump_name`
    - Important: for dump_name only type the name without .sql extension

## Execute a query
1. Run `bin/console mysql:query some-sql-query`

## Execute commands inside docker
1. Run `bin/console exec some-command`

## See more options
1. Run `bin/console`