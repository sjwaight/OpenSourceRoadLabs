### Tips for PHP (Laravel) + MySQL Lab.

Referring to: https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-php-mysql

The following will be useful to know.

* Ubuntu 14.04 hosts login issues with the Azure CLI (fails to authenticate in some instances). Consider Cloud Shell instead :smiley:
* Azure Database for MySQL - SSL challenge at present in client connections. Use the regional MySQL name (westus1-a.control.database.windows.net for example) in config and then instance name in login (user@instancename). See Note here: https://docs.microsoft.com/en-us/azure/mysql/howto-configure-ssl
* Needs PHP 5.6 or above (7 recommended).
* If you run on an Azure VM and want to publish your PHP app to internet, open Network Security Group and ensure that you run solution using: 

`sudo php artisan serve --host=0.0.0.0 --port=PORT-IN-NSG`
