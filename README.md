# Docker Compose Wordpress

```
docker compose up
```

Visit http://localhost:8080/ in a browser. Or log in to the admin UI with
user: `wordpress` and password: `wordpress`

## Local Development

⚠️ Database changes are not persisted ⚠️ (on purpose). To save your database work:

```
bin/sqldump
```
