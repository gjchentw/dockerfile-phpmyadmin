# gjchen/phpmyadmin@Dockerhub
PhpMyAdmin installed on a Flavored Alpine Linux

Usage:
```
docker run -d --name phpmyadmin \
   -e MYSQL_SERVERS="db1,db2,127.17.0.1"
   -p 80:80
   gjchen/phpmyadmin
```

If you wanna more customization, just overide the config file:
```
/etc/phpmyadmin/config.inc.php
```
