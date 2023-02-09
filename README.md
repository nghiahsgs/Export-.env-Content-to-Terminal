# Export-.env-Content-to-Terminal
Export .env Content to Terminal


I have .env file like below, I want to export all the content of this file to terminal

```
# MySQL
TRADING_DB_USER='root'
TRADING_DB_PWD='root'
TRADING_DB_HOST='localhost'
TRADING_DB_DATABASE='crm'
TRADING_DB_PORT=3308

# Redis
REDIS_HOST=redis
REDIS_PASSWORD=pass
REDIS_PORT=6379
```

Just simple do this command
```
source .env
```

here is the result
```
$ echo $TRADING_DB_USER
root
$ echo $TRADING_DB_PWD
root
$ echo $TRADING_DB_HOST
localhost
$ echo $TRADING_DB_DATABASE
crm
$ echo $TRADING_DB_PORT
3308
$ echo $REDIS_HOST
redis
$ echo $REDIS_PASSWORD
pass
$ echo $REDIS_PORT
6379
```
