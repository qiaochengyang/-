# mysql配置

skip-grant-tables
update mysql.user set authentication_string=password('*') where user='root';