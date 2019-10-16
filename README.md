# IT310

Prerequisites:
1.  PHPStorm and PHP
2.  MySQL Installed
3.  Database user and database created using PHPstorm
SQL Commands:
CREATE DATABASE wordpress;
CREATE USER "wordpress"@"localhost" IDENTIFIED WITH mysql_native_password BY 'password';
GRANT ALL PRIVILEGES ON wordpress.* TO "wordpress"@"localhost";

FLUSH PRIVILEGES;



Wordpress Setup

1. Download and extract wordpress
2. Open the directory in PHP storm
3. Copy wp-config-sample.php to wp-config.php
4. Edit wp-config.php to add the database connection info, where indicated by the comments
5. Setup run configuration for php built in server and run it
6. Visit localhost
