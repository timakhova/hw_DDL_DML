# Домашнее задание по лекции "Работа с данными (DDL/DML)" Тимахова Наталья

Задание 1

1. sudo mysql
2. CREATE USER 'sys_temp'@'localhost' IDENTIFIED BY 'password';
3. SELECT User, Host FROM mysql.user;
4. GRANT ALL PRIVILEGES ON *.* TO 'sys_temp'@'localhost';
FLUSH PRIVILEGES;
5. SHOW GRANTS FOR 'sys_temp'@'localhost';
6. mysql -usys_temp -p
7. ALTER USER 'sys_temp'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
8. SOURCE /home/timakhovanm/sakila-db/sakila-schema.sql;
SOURCE /home/timakhovanm/sakila-db/sakila-data.sql;
9. SHOW TABLES.

![1users](https://github.com/timakhova/hw_DDL_DML/blob/main/1-1users.png)
![2prava](https://github.com/timakhova/hw_DDL_DML/blob/main/1-2prava.png)
![3db](https://github.com/timakhova/hw_DDL_DML/blob/main/1-3db.png)

Задание 2

SHOW KEYS FROM table_name WHERE Key_name = 'PRIMARY';

![1tables](https://github.com/timakhova/hw_DDL_DML/blob/main/2-1tables.png)



