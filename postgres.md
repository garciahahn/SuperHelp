# Postgres
## Restoring a database from a dump

I have solved this by only using the common terminal. Following, demonstrating how it is done by example😋

```bash
psql -U postgres -d novdemo -f .\novdemo.pgsql
```

