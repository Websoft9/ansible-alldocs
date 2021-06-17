# Start or Stop the Services

These commands are required when you use the Alldocs of Websoft9.

### Alldocs

```shell
sudo systemctl start alldocs-server
sudo systemctl stop alldocs-server
sudo systemctl restart alldocs-server
sudo systemctl status alldocs-server

# you can use this debug mode if Alldocs service can't run
alldocs-server console
```

### MySQL

```shell
sudo systemctl start mysql
sudo systemctl stop mysql
sudo systemctl restart mysql
sudo systemctl status mysql
```

### Redis

```shell
sudo systemctl start redis
sudo systemctl stop redis
sudo systemctl restart redis
sudo systemctl status redis
```

### Docker
```shell
sudo systemctl start docker
sudo systemctl stop docker
sudo systemctl restart docker
sudo systemctl status docker
```

### phpMyAdmin on Docker
```shell
sudo docker inspect phpmyadmin
sudo docker start phpmyadmin
sudo docker restart phpmyadmin
sudo docker stop phpmyadmin
sudo docker rm phpmyadmin
```

### ONLYOFFICE Document Server on Docker
```shell
sudo docker inspect onlyofficedocumentserver
sudo docker start onlyofficedocumentserver
sudo docker restart onlyofficedocumentserver
sudo docker stop onlyofficedocumentserver
sudo docker rm onlyofficedocumentserver
```
