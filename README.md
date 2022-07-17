# docker-mysql-phpmyadmin
Provide an image of mysql and phpmyadmin

# Starting MYSQL image
- docker-compose up -d mysql

# Starting PHPMYADMIN image
- docker-compose up -d phpmyadmin

# Starting both at the same time
- docker-compose up -d

# Acessing PHPMYADMIN
- localhost:8080
- host: mysql
- user: root
- password: value informed in the MYSQL_ROOT_PASSWORD property of the docker-compose file
