---
layout: post
---
### mount network drive in WSL
- to check network drive name (window) : `wmic path win32_mappedlogicaldisk`
- mount to WSL : `sudo mount -t drvfs '\\[path]\[path]..' /mnt/[name]`

### set up Ubuntu
- version check : `lsb_release -a`
- upgrade with remove package if needed : `sudo apt full-upgrade`
- count files : `ls | wc -l`

### [install](https://laravel.com/docs/7.x/installation) PHP, apache, laravel
- `install apache / php : sudo apt install php libapache2-mod-php`
- `php --ini`
- `sudo apt install composer`
- `sudo apt install php-zip`
- `composer global require laravel/installer`
- `composer global about`
- `sudo apt install phpunit`

### start laravel
- `composer create-project --prefer-dist laravel/laravel [name]`
- `php artisan serve`
