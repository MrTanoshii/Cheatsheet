<div align="center">
  <a href="https://supabase.com/"><img src="https://github.com/devicons/devicon/blob/master/icons/supabase/supabase-original-wordmark.svg" title="Supabase" alt="Supabase" width="64" height="64"></a>
</div>

Further reading:

- [Documentation](#book-documentation)
- [SQL Scripts](#sql-scripts)

## :book: Documentation

https://supabase.com/docs

## SQL Scripts

### Grant permissions to schema & tables

Note: This opens access via `anon`.

```sql
GRANT usage ON schema "public" TO anon;
GRANT usage ON schema "public" TO authenticated;
GRANT usage ON schema "public" TO service_role;

GRANT SELECT, INSERT, UPDATE ON ALL TABLES IN SCHEMA "public" TO authenticated;
GRANT SELECT, INSERT, UPDATE ON ALL TABLES IN SCHEMA "public" TO anon;
GRANT SELECT, INSERT, UPDATE ON ALL TABLES IN SCHEMA "public" TO service_role;
```

### View permissions on schema tables

```sql
SELECT *
FROM information_schema.role_table_grants
WHERE table_schema='public'
```
