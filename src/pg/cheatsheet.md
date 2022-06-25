# Cheatsheet

Quick reference for PostgreSQL features that I use frequently

## [psql](https://www.postgresql.org/docs/current/app-psql.html)

* `\q` quit
* `\dn`: lists schemas (namespaces). Optionally takes a pattern to filter on: `\dn my_prefix*`
* `\d [S+]`: show details of each relation that matches the given pattern. Lists all if not given a pattern.
  * Examples: `\d my_table` for a single relation or `\d my_prefix*` for all relations matching a prefix
* `\dt [S+]`: similar to `\d` but only for tables
* `\dT`: lists data types. Can get more info with `\dT+`

## [DDL](https://www.postgresql.org/docs/current/ddl.html)

* `SHOW search_path;`: shows the current schema search path
* `SET search_path TO myschema;`: sets schema search path to given path. There can be multiple: `SET search_path to myschema,public;`
