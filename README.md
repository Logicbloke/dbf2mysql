# dbf2mysql
PHP dBase to MySQL mapping and import tool

It's using a port of the PHPXBase class by [luads](https://github.com/luads/php-xbase). Just copy the folder on your web server and open the page in the browser.

Configuration
----
Make sure you update your db credentials in the index.php file.

Usage
----
1. The first phase lets you upload a .dbf file as well as choose from one of the tables on the MySQL database from the active connection.
2. The 2nd phase lets you map fields from the dbf file to the table.
3. Last phase starts the import process and reports with a count of records imported at the end. If any errors during the import, it should tell you.