# mysql-password-setup-solution


      mysql -V    (ENSURE IT IS 8.0.32-0ubuntu0.22.04.2 WITHIN THIS RANGE OF 8. SOMETHING )
       sudo /etc/init.d/mysql stop 
       sudo mkdir /var/run/mysqld
       sudo chown mysql /var/run/mysqld
       sudo mysqld_safe --skip-grant-tables&          (PRESS ENTER ONCE It has shown [1])
       sudo mysql --user=root mysql
