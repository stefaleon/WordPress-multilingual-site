## Create a multilingual website with WordPress

### Local server, database and WordPress installation
* Setup XAMPP.
* In *xampp/htdocs* uncompress the latest WordPress version.
* Rename the *wordpress* folder to the desired name, e.g. *siteName*.
* Start Apache and MySQL from the XAMPP control panel.
* Typing *localhost* in the browser will redirect to *localhost/dashboard*. From there phpMyAdmin can be accessed.
* In *http://localhost/phpmyadmin/* create an SQL database by assigning the desired name, e.g. *dbName*.
* Inside the *siteName* folder, rename a copy of *wp-config-sample.php* to *wp-config.php*.
* In *wp-config.php* define the *'DB_NAME'*, set it to *'dbName'*.
* Define define the *'DB_USER'*, set it to *'root'*.
* Define define the *'PASSWORD'*, set it to *''*.
* Now typing *localhost/siteName* in the browser redirects to *http://localhost/siteName/wp-admin/install.php*.
* Select the installation language and provide the site title, username, password and email.
