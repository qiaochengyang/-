# mysql配置

skip-grant-tables
sudo mysql -uroot
update user set authentication_string=password("*"),plugin='mysql_native_password' where user='root';
