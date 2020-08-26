# sql-snippets README

SQL-Snippets provides code snippets for creating idempotent SQL. Idempotency is especially important when creating database migration scripts.

A SQL script can be described as idempotent when it can be applied multiple times without changing the result beyond the initial application.

## Features

| Command       | Postgres Prefix |
| ------------- |:-------------:|
| Create Schema | psql - Create new schema |
| Drop Schema   | psql - Drop exisiting schema |
| Create Table  | psql - Create new table |
| Drop Table | psql - Drop existing table |
| Add Column | psql - Add new column |
| Drop Column | psql - Drop a column |
| Add Constraint | psql - Add new constraint |
| Drop Constraint | psql - Drop existing constraint |
| Add Index | psql - Add index |
| Drop Index | psql - Drop index |

