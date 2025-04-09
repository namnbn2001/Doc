# Postgres

Connect to PostgreSQL

```nginx
psql -U your_username -d your_database
```

## Basic psql command

List all databases

```sql
\l
```

Connect to a different database

```sql
\c database_name
```

List all tables in the current database

```sql
\dt
```

Exit

```sql
\q
```

Check Connection

```sql
\conninfo
```

### User

Verify Existing Users

```sql
\du
```

Set or Change the Password

```sql
ALTER ROLE username WITH PASSWORD 'new_password';
```
