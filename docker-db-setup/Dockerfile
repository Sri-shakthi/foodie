FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=root
COPY ./database-wormconnect.sql /docker-entrypoint-initdb.d
EXPOSE 3306