Dynamic Charts with PHP and PostgreSQL Database
===
A simple example for creating single-series dynamic chart using FusionCharts PHP Wrapper with data from PostgreSQL.

![Dynamic Chart](https://s2.postimg.org/xilccl96x/Screen_Shot_2017-05-03_at_10.08.51_PM.png)

Steps to run the sample:
---

* Import `browsershare.sql` to your Postgres database.
+ Update connection string variables for database host, database port, database name, postgres database username and password in `index.php`.
	+ Please make sure you have enabled `extension=php_pdo_pgsql.dll` and `extension=php_pgsql.dll` in your `php.ini` configuration file.

```
$host= "host="; // database host name
$port= "port="; // postgres database port
$dbname="dbname="; // name of database
$dbuser="user="; // postgres database user
$dbpwd="password="; // postgres database user password
```
+ Run `index.php`.

Got questions? Open an [issue](https://github.com/sikrigagan/Dynamic-PHP-PostgreSQL-Charts/issues/new) or feel free to say hi on [Twitter](https://twitter.com/sikrigagan)!
