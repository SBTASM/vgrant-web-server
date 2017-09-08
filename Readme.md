<h2>Vagrant WEB Server (yii2 modified)</h2>
Packages:
<ol>
    <li>php7.0-curl</li>
    <li>php7.0-cli</li>
    <li>php7.0-intl</li>
    <li>php7.0-mysqlnd</li> 
    <li>php7.0-gd</li>
    <li>php7.0-fpm</li> 
    <li>php7.0-mbstring</li> 
    <li>php7.0-xml</li> 
    <li>unzip</li> 
    <li>nginx</li> 
    <li>mysql-server-5.7</li>
    <li>php-xdebug</li>
</ol>
Extern:
<ol>
    <li>composer</li>
    <li>fxp/composer-asset-plugin 1.3.1</li>
</ol>
Nginx config on 'vagrant/nginx/app.conf', xdebug - 'vagrant/xdebug/xdebug.ini'.
Xdebug default enabled.

Requirements:
<ol>
    <li>vagrant-hostmanager(vagrant install plugin vagrant-hostmanager)
    <li>VirtualBox/VmWare(tested on Windows 7/8.1/10 and Linux OpenSuse 13.2/43.2, Unbuntu 16.04, Debian 8)
</ol>