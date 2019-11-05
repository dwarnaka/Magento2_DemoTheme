# Magento2_DemoTheme

Setting up Magento 2.3.x on Ubuntu 18.04

1.  sudo apt-get install php7.2 php7.2-common php7.2-mbstring php7.2-xmlrpc php7.2-soap php7.2-gd php7.2-xml php7.2-intl php7.2-mysql php7.2-cli php7.2-bcmath php7.2-ldap php7.2-zip php7.2-curl php7.2-bcmath -y

2.  sudo chown -R www-data:www-data /var/www/html
    sudo chmod -R 755 /var/www/html
    
3.  Apache configuration
    <Directory /var/www/html/>
        Options FollowSymLinks MultiViews
        AllowOverride All
     </Directory>
