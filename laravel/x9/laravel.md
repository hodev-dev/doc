# Install PHP Ubuntu 20.04.5 LTS
```bash
sudo apt install software-properties-common
```
```bash
sudo add-apt-repository ppa:ondrej/php -y
```
```bash
sudo apt update -y && sudo apt upgrade -y
```
```bash
sudo apt install php8.1 php8.1-fpm php8.1-cli php8.1-curl php8.1-zip php8.1-mysql php8.1-mbstring php8.1-xml php8.1-bcmath
```
## version
```
php8.1
```
# Install Composer
``` 
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
```
```
php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
```
```
php composer-setup.php
```
```
php -r "unlink('composer-setup.php');"
```
```
sudo mv composer.phar /usr/local/bin/composer
```
export path to ```.bash_profile```
```
export PATH="~/.config/composer/vendor/bin:$PATH"
```
## version
```
Composer version 2.4.4 2022-10-27 14:39:29
```