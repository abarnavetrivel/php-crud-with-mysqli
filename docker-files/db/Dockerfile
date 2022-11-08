FROM mysql:5.7.25

LABEL "Author"="Abarna"

ENV MYSQL_ROOT_PASSWORD="dbpassword"
ENV MYSQL_DATABASE="users"


ADD db_backup.sql docker-entrypoint-initdb.d/users.sql
