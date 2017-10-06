FROM mysql

RUN service mysql start
COPY init.sql /docker-entrypoint-initdb.d/init.sql

