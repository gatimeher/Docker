docker pull centos/mysql-57-centos7
docker run -d --name mysql_database -e MYSQL_USER=user -e MYSQL_PASSWORD=pass -e MYSQL_DATABASE=db -p 3306:3306 centos/mysql-57-centos7
