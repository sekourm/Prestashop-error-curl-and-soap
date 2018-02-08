# Prestashop-error-curl-and-soap
Prestashop error curl and soap

<pre>
vim /etc/php/7.1/cli/php.ini
</pre>

uncomment the line

<pre>
;extension=php_curl.dll
;extension=php_soap.dll
</pre>

install soap and curl if is not installed

<pre>
sudo apt-get install php7.1-soap
sudo apt-get install php7.1-curl
sudo systemctl restart apache2.service
</pre>
