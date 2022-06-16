#Configure ELK to work with mysql slow query log


### Setup

```
docker-compose up
python3 load/mysql.py
```

### Access to logs
```
http://localhost:5601/app/logs/stream
elastic
qwerty
```

### Screenshot
![Kibana](./screenshots/elk.png?raw=true "Kibana")