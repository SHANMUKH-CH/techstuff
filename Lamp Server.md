# LAMP (Linux + Apache + MySQL + PHP)
A plethora of Open Source applications written using the LAMP application stack
### 1. Linux installation
After installing [Linux](https://www.wikihow.com/Install-Linux) run
```
$sudo apt-get update
```
### 2. Apache installation
Apache HTTP Server is a free and open-source web server that delivers web content through the internet.
```
$sudo apt install apache2
```
### 3. MySQL installation
Database management system
```
$sudo apt install mysql-server
```
### 4. PHP installation
A general-purpose scripting language especially suited to web development.
```
$sudo apt install php-pear php-fpm php-dev php-zip php-curl php-xmlrpc php-gd php-mysql php-mbstring php-xml libapache2-mod-php
```
### Start the services
Restart server
```
$sudo service apache2 restart
```
Check Apache working or not by navigating to
[LocalHost](http://localhost/.) &
Check PHP in terminal
```
$php -r 'echo "\n\nYour PHP installation is working fine.\n\n\n";'
```
### your LAMP is working!!!
