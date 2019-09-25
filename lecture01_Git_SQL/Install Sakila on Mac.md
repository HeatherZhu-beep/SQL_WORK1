# Set up sakila sample database

1. Install MySQL community server
2. Download [sakila database](https://downloads.mysql.com/docs/sakila-db.zip)
3. Open MySQL terminal

```bash
/usr/local/mysql/bin/mysql -hlocalhost -uroot -ppassw0rd
```

4. Import DB schema

```bash
source /path/to/sakila-schema.sql
```

5. Import DB data

```bash
source /path/to/sakila-data.sql
```
