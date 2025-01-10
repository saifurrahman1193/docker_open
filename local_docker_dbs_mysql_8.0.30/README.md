# Network
```
sudo docker network create local_central_db_network
```

# Command : Docker : Setup : Initialized
```
sudo docker-compose down
sudo docker-compose build && docker-compose up -d
```


# Attach Shell
```
python --version
```

# Open in browser

# Run directly/terminally without vscode
```
sudo chmod 777 -R *
docker start local-central-db-container-8.0.30
docker exec -it local-central-db-container-8.0.30 bash
chown 644 /etc/mysql/my.cnf
mysql -u root -p
Ro@t1234

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'Ro@t1234';
SHOW DATABASES;
```