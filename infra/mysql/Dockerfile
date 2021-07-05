FROM mysql:8

ADD ./mysql /etc/mysql/my.cnf
RUN chmod 644 /etc/mysql/my.cnf

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]
