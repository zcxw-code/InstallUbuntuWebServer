> # InstallUbuntuWebServer - руководство по установке веб-сервера Ubuntu




1. Для начала вам необходимо скачать пакеты [XAMPP](https://www.apachefriends.org/ru/download.html) для linux. 
2. `sudo chmod +x xampp-linux-x64-7.2.29-1-installer.run`
3. `sudo ./xampp-linux-x64-*-installer.run`
4. `sudo /opt/lampp/lampp start`
5. `nano /etc/hosts`
   > Добавить lampp и xampp, а также если хотите ваш домен: `127.0.0.1 localhost lampp xampp or 127.0.0.1 localhost lampp xampp you_domain`
6. `sudo /opt/lampp/lampp restart`
