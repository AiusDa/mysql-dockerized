# MYSQL DOCKERIZED WITH CLI
MySQL Dockererized with CLI to import and export databases.

The CLI is inspired by the [Dockerized Magento 2](https://github.com/arvatoSCM/dockerize-magento2) project.

## Usage
1. Download this project
2. Run `sudo chmod +x bin/console` to give CLI permissions to run
3. Run `bin/console start`
4. Enjoy it

## Import databases
1. Copy into dumps folder your dump
2. Run `bin/console mysql:import dump_name database_name`
    - Important: for dump_name only type the name without .sql extension

## Create a dump
1. Run `bin/console mysql:dump database_name dump_name`
    - Important: for dump_name only type the name without .sql extension

## Execute a query
1. Run `bin/console mysql:query some-sql-query`

## See more options
1. Run `bin/console`