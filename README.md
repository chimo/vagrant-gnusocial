# Vagrant image for GNU social

Status: experimental

Use the Vagrant file in this repository or copy the configs to yours.  
Run `vagrant up --provider virtualbox`

Note: The GNU social instance has been setup on port 8080.  
If you need to change this, you'll need to udpate the port in the Vagrant file
as well as the port in the GNU social config.php (/srv/http/gnusocial/public_html/config.php)

## Stack

* Archlinux (2015-11-01)
* nginx
* php-fpm (zend opcache + apcu)
* mariadb
* GNU social (git: 2015-11-04)

## Credentials

### Database

db: gnusocial  
user: gnusocial  
password: gnusocial

### GNU social

user: admin  
password: admin

