# setup-server
step setup web server ubuntu</br>
install server</br>
sudo apt-get update && sudo apt-get upgrade</br>
sudo apt-get install apache2</br>
sudo apt-get install mysql-server</br>
mysql -u root -p</br>
exit;</br>
sudo apt-get install php php-mysql libapache2-mod-php php-cli php-cgi php-gd mysql-server mysql-client zip -y</br>
sudo apt-get install phpmyadmin</br>
sudo ln -s /etc/phpmyadmin/apache.conf /etc/apache2/conf-available/phpmyadmin.conf</br>
sudo a2enconf phpmyadmin.conf</br>
sudo systemctl restart apache2</br>
