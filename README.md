# setup-server
step setup web server ubuntu
install server
sudo apt-get update && sudo apt-get upgrade
sudo apt-get install apache2
sudo apt-get install mysql-server
mysql -u root -p
exit;
sudo apt-get install php php-mysql libapache2-mod-php php-cli php-cgi php-gd mysql-server mysql-client zip -y
sudo apt-get install phpmyadmin
sudo ln -s /etc/phpmyadmin/apache.conf /etc/apache2/conf-available/phpmyadmin.conf
sudo a2enconf phpmyadmin.conf
sudo systemctl restart apache2
