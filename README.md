# PostgreSQL Cheat Sheet
PostgreSQL (psql) commands in one page for the SQL REPL from [postgresql.org](https://www.postgresql.org/docs/10/static/index.html).

<img src="https://i.imgur.com/nueSCcH.gif" width="250">

## Basics
| Name | Description |
|------|-------------|
| `psql` | Connect to the database. |
| `psql -d pg_data_base -U pg_user` | Connect to localhost `pg_data_base` as `pg_user`. |
| `create user pg_user with password 'pguserpassword';` | Create a user `pg_user`. |
| `create database pg_database owner pg_user;` | Create a database with name `pg_database` which belongs to `pg_user`.


## General Purpose
| Name | Description |
|------|-------------|
| `\q` | Quit from psql. |
| `\l` | Lists all the databases. |
| `\dn` | List schemas. |
| `\dt` | List tables in connected database. |
| `\d table_name` | List columns on table. |
| `\df` | List functions |
| `\dv` | List views. |
| `\x auto` | Super pretty query output for long rows. |
| `\t` | Turn off/on output header and row count. |

Help me to fill out the rest useful commands which you think might be helpful to use on daily basis.
