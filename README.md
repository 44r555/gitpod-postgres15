# gitpod-postgres-database

GitPod demo repository with PostgreSQL

Inspired by Lucas Jellema's work at https://github.com/lucasjellema/gitpod-oracle-database.git

[™️![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/?autostart=true&editor=code&workspaceClass=g1-large#https://github.com/44r555/gitpod-postgres15) <BR/>
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/martijnpronkAMIS/gitpod-postgres-database)

PostgreSQL 15 database running in a docker container called postgresDB15.
The database is initialized, VS code extension added to allow connecting to that database. 
A database user and database are created: testuser / welkom01 database testdb.

A terminal to the Postgres "Root" user is opened automatically.

Quick hints in the terminal:
```
\l              list databases in Postgres Cluster
\d              list tables in current database viewable for the current user
\d <table_name> show table's definition

```

