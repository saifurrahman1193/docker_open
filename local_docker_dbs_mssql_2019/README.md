# Network : External Network
```
docker network create local_central_db_network
```

# Command : Docker
```
sudo docker-compose down
sudo docker-compose build && docker-compose up -d
```

# Connect with a client
```
server: localhost
user: sa
password: P@ssword123
port:1433
```

# Command : Docker
```
mysql -h localhost -u root -p 
root
ALTER USER root@localhost IDENTIFIED WITH mysql_native_password BY 'Ro@t123456789';
FLUSH PRIVILEGES;
```

```
CREATE USER 'saifur'@'%' IDENTIFIED BY 'saifur';
GRANT ALL PRIVILEGES ON *.* TO 'saifur'@'%';
mysql -h localhost -u saifur -p 
saifur
```


https://learn.microsoft.com/en-us/sql/linux/quickstart-install-connect-ubuntu?view=sql-server-ver16&tabs=ubuntu2004