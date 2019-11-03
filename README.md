# world
Installation
The SQL file includes create statements with indexes, so simply follow the steps below to import the sql file.

Linux/OSX command line:

$ gunzip world.sql.gz
$ mysql -u myusername -p mypassword
mysql> use mydatabase;
mysql> source world.sql;
