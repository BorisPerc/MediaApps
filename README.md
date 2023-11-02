# Media Apps - Media Server php/SQL WEB App
Media Apps base on php/SQL - Media/Audio Server - install apps for php7.4 Apache/Nginx - Media Servers base on php/SQL WEB Applications. 
Install WEBApps on your WindowsNT Server or Linux Server - Apache/Nginx + SQL + php7.4 + extra phpmyadmin + obligatory FFmpeg binary file path: on Linux(/usr/bin/ffmpeg) or Windows(C:\\ffmpeg\bin\ffmpeg.exe) + extra obligatory php-modules


# 1. Media Shareing and playing music, generating play lists,....
Audio Server php7.2+, Ampache5-Compact-7.4, SoundCloud/DeepSound-CompactExtra-7.2+

# 1.1. Audio Server - php/SQL WEB App mp3player
Upload and unzip audio.zip in your root directory of your domain or subdomain /htdocs/ or /var/www/html/ or /home/www/ .... your vhost root.

Generate database, user and pass for app in SQL10 or Xampp Windows/Macintosh phpmyadmin generate database for application:

sudo mariadb

CREATE DATABASE audio;

CREATE USER 'audio'@'localhost' identified by 'password';

GRANT ALL PRIVILEGES ON audio.* to 'audio'@'localhost';

FLUSH PRIVILEGES;

quit


Now edit database.php and input your data generated for Audio Server and open VHost URL: 

http://www.mydomain.com/

http://www.mydomain.com/setup.php

And login no password localplayer

# 1.2. Ampache Compact editon for php7.4 Media Server

Upload all ampache.zip files for example on your desktop ampache.zip ampache.z01 ampache.z02 and open zip file and unpack files to desktop.

After Unpacked multi pack and upload ampache.zip to your root directory for example /home/admin/htdocs/ or /var/www/mydomain.com/

Make in phpmyadmin database, user and password or terminal for example SQL10

sudo mariadb

CREATE DATABASE ampache;

CREATE USER 'ampache'@'localhost' identified by 'password';

GRANT ALL PRIVILEGES ON ampache.* to 'ampache'@'localhost';

FLUSH PRIVILEGES;

quit

INSTALL open VHost URL: 

http://www.mydomain.com/

http://www.mydomain.com/install.php

# 1.3. DeepSound Compact editon for php7.2+/8.1 Media Server

Upload all ampache.zip files for example on your desktop deepsoundnew.zip deepsoundnew.z01 deepsoundnew.z02 deepsoundnew.z03 deepsoundnew.z04 and open zip file and unpack files to desktop.

Unpacked multi pack and upload ampache.zip to your root directory for example /home/admin/htdocs/ or /var/www/mydomain.com/

After ampache.zip Unpacked multi pack zip upload deepsound152install.zip to your root directory for example /home/admin/htdocs/ or /var/www/mydomain.com/

Make in phpmyadmin database, user and password or terminal for example SQL10

sudo mariadb

CREATE DATABASE deepsound;

CREATE USER 'ampache'@'localhost' identified by 'password';

GRANT ALL PRIVILEGES ON deepsound.* to 'deepsound'@'localhost';

FLUSH PRIVILEGES;

quit

INSTALL open VHost URL: 

http://www.mydomain.com/

http://www.mydomain.com/install/


