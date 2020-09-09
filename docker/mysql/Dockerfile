FROM mysql:5.7

#ポートを開ける
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./my.cnf /etc/mysql/conf.d/my.cnf
# COPY ./initdb.d/* /docker-entrypoint-initdb.d/

CMD ["mysqld"]
