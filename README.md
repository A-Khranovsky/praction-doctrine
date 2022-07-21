## Vocation
Praction with Doctrine package and it's support packages, creation the table in DB using entity and 
annotations.

## Description
Project can create table products in th DB. In use DBMS PostgreSQL. Config file (bootstrap.php)
is tuned to use that DBMS.

To update the DB schema was used command:
```
vendor\bin\doctrine orm:schema-tool:update --force --dump-sql
```