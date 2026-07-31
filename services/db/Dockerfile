FROM docker.io/mysql:8.0

ENV MYSQL_ROOT_PASSWORD=111111 \
    MYSQL_DATABASE=englitopia

ADD services/db/dump.sql /docker-entrypoint-initdb.d

CMD ["mysqld -uroot -p111111"]
