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
mysql --user=root mysql

update user set Password=PASSWORD('root') where user='root';
flush privileges;
exit;


 ALTER USER 'root'@'localhost' IDENTIFIED BY root;
 update user set authentication_string=PASSWORD("root") where User='root';

MYSQL_USER: root
MYSQL_PASSWORD: root
MYSQL_ROOT_PASSWORD: root
PORT: 3377
```