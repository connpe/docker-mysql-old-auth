# connpe/mysql-old-auth

Docker build using MySQL 8 distribution but with the old authentication mechanism set as the default so that php applications
which rely on this mechanism will work with MySQL 8.

Change to /etc/mysql/my.cnf
- default-authentication-plugin=mysql_native_password
 
Otherwise see the Docker Official Images MySQL page https://hub.docker.com/_/mysql

