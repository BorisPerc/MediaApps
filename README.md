# Media Apps - Media Server php/SQL WEB App
Media Apps base on php/SQL - Media/Audio Server - install apps for php7.4 Apache/Nginx

1. Media Shareing and playing music, generating play lists,....
Audio Server, Ampache-Compact, SoundCloud

1.1. Audio Server - php/SQL WEB App mp3player
Upload and unzip audio.zip in your root directory of your domain or subdomain /htdocs/ or /var/www/html/ or /home/www/ .... your vhost root.

Generate database, user and pass for app in SQL10 or Xampp Windows/Macintosh phpmyadmin generate database for application:

sudo mariadb

CREATE DATABASE audio;

CREATE USER 'audio'@'localhost' identified by 'password';

GRANT ALL PRIVILEGES ON audio.* to 'audio'@'localhost';

FLUSH PRIVILEGES;

quit


Now edit database.php and input your data generated for Audio Server and open VHost URL: http://www.mydomain.com/
http://www.mydomain.com/setup.php

And login

