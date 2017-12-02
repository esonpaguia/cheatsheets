# MySQL

## How to change root password
- Login to MySQL CLI
```
$ mysql -u root -p
```
- Change password
```
mysql> ALTER USER 'root'@'localhost' IDENTIFIED BY 'new_password_here'
```