FROM mysql:latest
COPY init.sql /docker-entrypoint-initdb.d/init.sql
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=appdb
ENV MYSQL_USER=appuser
ENV MYSQL_PASSWORD=apppass
