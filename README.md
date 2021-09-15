# PostgreSQL Tips & Tricks

Some Tips and Tricks about PostgreSQL.

[![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/contains-technical-debt.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

![PostgreSQL](./images/postgresql-logo-256.png)

## Useful scripts

### Audit

* [Get content statistics for a table](./scripts/audit/table-statistics.sql)
* [Check a fillfactor value for tables and indexes](./scripts/audit/fill-factor-value.sql)
* [Find duplicate indexes](./scripts/audit/duplicate-indexes.sql)
* [Find useless indexes](./scripts/audit/useless-indexes.sql)
* [Get the table structure](./scripts/audit/table-structure.sql)
* [Get index usage statistics](./scripts/audit/index-usage-statistics.sql)
* [Tables needing indexes](./scripts/audit/tables-need-indexing.sql)
* [Returns all non-system tables missing a primary key and (or) unique indexes](./scripts/audit/tables-without-pk-ui.sql)
* [Returns all non-system tables on which a primary key is missing](./scripts/audit/tables-without-pk.sql)
* [Returns all tables with Geometry fields that have no index on the Geometry field](./scripts/audit/tables-without-indexes-on-geometry.sql)
* [Find bloated tables](./scripts/audit/find_bloated_tables.sql)
* [Find missing indexes](./scripts/audit/missing-indexes.sql)

### Size

* [Checking the size of the database](./scripts/size-related-issues/db-size.sql)
* [Get wasted bytes](./scripts/size-related-issues/wasted-bytes.sql)
* [Which table has the highest dead tuples](./scripts/size-related-issues/dead-tuples.sql)
* [Which table or index is consuming the most space](./scripts/size-related-issues/most-space.sql)

### Performance

* [Top 10 longest queries](./scripts/performance-related-issues/top-10-longest-queries.sql)
* [Get running queries and lock statuses](./scripts/performance-related-issues/running-queries.sql)
* [Kill a query](./scripts/performance-related-issues/kill.sql)

### Security

* [Return user grants](./scripts/security/user-grants.sql)

## Useful links

* [PostgreSQL SQL Tricks](https://postgres.cz/wiki/PostgreSQL_SQL_Tricks) - Tips & Tricks on PostgreSQL
* [PostgreSQL Index Maintenance](https://wiki.postgresql.org/wiki/Index_Maintenance) - Index maintenance
* [Postgres Cheat Sheet](https://postgrescheatsheet.com/#/tables) - PGSQL cheat sheet
* [PGSQL commands & queries](https://dzone.com/articles/useful-postgresql-commandsqueries-part-1) - Useful commands & queries

## Tomorrow I will learn

* [pgwatch](https://www.cybertec-postgresql.com/en/products/pgwatch/) - PG monitoring tool
* [pg_configurator](https://www.cybertec-postgresql.com/en/products/pg-configurator/) - Configurating PG
* [pg_squeeze](https://www.cybertec-postgresql.com/en/products/pg_squeeze/) - Shrink PG tables
* [pgTAP](https://pgtap.org/) - Unit testing for PostgreSQL

## Build with

* [Git](https://git-scm.com) - Open source distributed version control system

## Contributing

If you would like to contribute, read the CONTRIBUTING.md file to learn how to do so.
