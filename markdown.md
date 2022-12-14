## Documentation for project 1 (LAMP STACK IMPLEMENTATION)

`sudo apt update`

![apache installation](./images/packages_update.PNG)

`sudo apt install apache2`

![apache status](./images/apache_package_configuration_pending_kernel_upgrade.PNG)

![apache status](./images/apache_package_configuration_outdated_libraries.PNG)

![apache status](./images/packages_update.PNG)

`sudo systemctl status apache2`

![apache status](./images/apache_status_4.PNG)

Opened inbound connection through port 80

![port 80 status](./images/port_80_opened.PNG)

`curl http://localhost:80`

![apache http server response](./images/apache_http_server_response_page1.PNG)

![apache http server response](./images/apache_http_server_response_page2.PNG)

![apache http server response](./images/apache_http_server_response_page3.PNGg)

![apache http server response](./images/apache_http_server_response_page4.PNG)

![apache http server response](./images/apache_http_server_response_page5.PNG)

![apache http server response](./images/apache_http_server_response_page6.PNG)

![apache http server response](./images/apache_http_server_response_page7.PNG)

![apache http server response](./images/apache_http_server_response_page8.PNG)

![apache http server response](./images/apache_http_server_response_page9.PNG)

[apache http](http://13.38.130.39)

![apache http request response](./images/apache_http_request_response.PNG)

`curl -s http:/13.38.130.39/latest/meta-data/public-ipv4`

![curl response](./images/public_ip_address_retrieval.PNG)

`sudo apt install mysql-server`

![mysql server installation](./images/mysql_installation/mysql_installation_page1.PNG)

![mysql server installation](./images/mysql_installation/mysql_installation_page2.PNG)

`sudo mysql`

![sudo mysql response](./images/mysql_installation/sudo_mysql_response.PNG)

`sudo mysql_secure_installation`

![sudo mysql secure installation](./images/mysql_installation/sudo_mysql_secure_installation_page1.PNG)

![sudo mysql secure installation](./images/mysql_installation/sudo_mysql_secure_installation_page2.PNG)

`sudo mysql -p`

![mysql console login](./images/mysql_installation/sudo_mysql_-p_response.PNG)

`sudo apt install php libapache2-mod-php php-mysql`

![php](./images/php_installation/php_installation_page.PNG)

`php -v`

![php version](./images/php_installation/php_version.PNG)







