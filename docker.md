# Docker

## Configure a we development enviroment

* Install docker, wsl and vs code.
* On linux terminal inside vscode, install php-apache:
<br><code>docker pull php:7.4-apache</code>

* Create a <i>dockerfile</i> containing:
<br><code>FROM php:7.2-apache</code>
<br><code>COPY src/ /var/www/html/</code>

* On linux terminal inside vscode:
<br><code>docker build -t my-php-app .</code>
<br><code>docker run -d --name my-running-app my-php-app</code>