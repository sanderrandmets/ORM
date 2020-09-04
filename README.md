

kontollisin PHP versiooni : php -v
Kui pole PHP-d siis laadisime ubuntusse: sudo apt install php7.4-cli

sudo add-apt-repository ppa:ondrej/php
sudo apt update
Extensionite installimise 1 näidetest: sudo apt install php7.4-bcmath

sudo apt install composer
kontollisin composeri versiooni : composer -v
installisin Zip extensioni: sudo apt install php7.4-zip

composer global require laravel/installer
composer create-project --prefer-dist laravel/laravel blog
cd blog/
ls -al
code .