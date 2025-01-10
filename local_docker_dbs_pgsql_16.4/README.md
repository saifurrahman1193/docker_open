# Network
```
sudo docker network create local_central_db_network
```

# Command : Docker : Setup : Initialized
```
sudo docker-compose down
sudo docker-compose build && docker-compose up -d
```

# Connect in command line
```
docker exec -it local-central-db-pgsql-container-16.4 bash
psql -U root
\q
```

# remote allow
```
allow port inbound 5432
pg_hba.conf
host    all    all    0.0.0.0/0    md5
```