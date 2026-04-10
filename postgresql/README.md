<div align="center">
    <a href="https://www.postgresql.org/"><img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="64" height="64"></a>
</div>

## Table of Contents

- [Documentation](#book-documentation)

## :book: Documentation

Website: https://www.postgresql.org/

## Connect

```bash
psql -U <USERNAME> -d <DATABASE_NAME>
```

## Dump & Restore

```bash
# Dump the database
pg_dump -U <USERNAME> -h <HOST> -p <PORT> -d <DATABASE_NAME> -F c -b -v -f <OUTPUT_FILE>

# Restore the database
pg_restore -U <USERNAME> -h <HOST> -p <PORT> -d <DATABASE_NAME> -v <INPUT_FILE>
```
