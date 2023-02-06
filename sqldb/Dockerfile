FROM mysql:5.7
LABEl "admin"="vicky"
LABEL "projectname"="test"
ENV MYSQL_ROOT_PASSWORD="sqlpass"
ENV MYSQL_DATABASE="accounts"
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
