# PostgreSQL Tips & Tricks

Some Tips and Tricks about PostgreSQL.

[![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/contains-technical-debt.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

![PostgreSQL](./images/postgresql-logo-256.png)

## Useful scripts

* Get content statistics for a table
* Check a fillfactor value for tables and indexes
* Find duplicate indexes
* Return user grants
* Find useless indexes
* Get the table structure
* Get index usage statistics
* Find missing indexes
* Returns all non-system tables missing a primary key and (or) unique indexes
* Returns all non-system tables on which a primary key is missing
* Returns all tables with Geometry fields that have no index on the Geometry field
* Top 10 longest queries

## Useful links

* [SqlBench](https://github.com/felixge/sqlbench) - Tool to measures and compares the execution time of SQL queries on PG database
* [PostgreSQL SQL Tricks](https://postgres.cz/wiki/PostgreSQL_SQL_Tricks) - Tips & Tricks on PostgreSQL
* [PostgreSQL Index Maintenance](https://wiki.postgresql.org/wiki/Index_Maintenance) - Index maintenance
* [Postgres Cheat Sheet](https://postgrescheatsheet.com/#/tables)

## Tomorrow I will learn

* [pgwatch](https://www.cybertec-postgresql.com/en/products/pgwatch/) - PG monitoring tool
* [pg_configurator](https://www.cybertec-postgresql.com/en/products/pg-configurator/) - Configurating PG
* [pg_squeeze](https://www.cybertec-postgresql.com/en/products/pg_squeeze/) - Shrink PG tables
* [pgTAP](https://pgtap.org/) - Unit testing for PostgreSQL

## Build with

* [PostgreSQL](https://www.postgresql.org) - Open source object-relational database system
* [Docker](https://www.docker.com/) - Set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers
* [Git](https://git-scm.com) - Open source distributed version control system
* [pgAdmin](https://www.pgadmin.org/) - Open Source administration and development platform for PostgreSQL
* [Go](https://golang.org/) - Open source programming language 

## Getting started with SqlBench

* Clone this project
* Use docker-compose and the docker-compose.yaml file

```bat
docker-compose up -d
```

* Install Go
* Install Sqlbench with Go

```go
go get -u github.com/felixge/sqlbench
```

* Call Sqlbench in CL

```bat
sqlbench -c postgres://admin:password@localhost:5432/adventureworks?sslmode=disable -n 1000 -o baseline.csv queries/employee.sql
```

* Use docker-compose to stop properly the project

```bat
docker-compose down
```

## Contributing

If you would like to contribute, read the CONTRIBUTING.md file to learn how to do so.
