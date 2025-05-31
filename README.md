# apache2

update:
apt update 
apt upgrade 

install:
apt install apache2

start apache2:
systemctl start apache2

enable vendot preset:
systemctl enable apache2

chech the status:
systemctl status apache2
or 
systemctl status httpd 

acsses the website:
localhost

edit the website 
nano /var/www/html/index.html 
