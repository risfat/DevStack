# DevStack
DevStack is a shell script. This Script will install all the programs of LAMP & LEMP Stack Development automatically on your debian or ubuntu based linux distro. It's super easy to use.

> *Unfortunately this script is only for debian or ubuntu based distro's. I'm not so much familier with Arch, openSUSE or Fedora yet. So I can't make this script for them. But if any one of them who know bash scripting and use Arch/OpenSUSE/Fedora, they're mostly welcome to contribute on this repository. I'll be thankful and willing to give credit to them.*

# Which Program will it install automatically?
DevStack can install
1. Apache
2. Nginx
3. MySql
4. phpMyAdmin
5. PHP
6. IpTable
7. UFW
8. Composer
9. Laravel CLI
10. VUE CLI
11. Node.js v16.x
12. Git
13. Build Essential packages
14. curl

Gyro Pilot isn't about to only install programes automatically. It will also Configure all the programs automatically. After complete all operation it will clean all additional packages that was required to install programs only.

# Some basic information
1. Nginx configuration path is = `/etc/nginx/conf.d/`
2. phpMyAdmin root path is = `/usr/share/phpmyadmin/`
3. phpMyAdmin Symbolic path is = `/var/www/phpMyAdmin/`
4. Web Directory = `/var/www/`
5. Localhost URL = `http://localhost` , `192.168.xxx.xxx` (Your router IP that assigned to your device.), `127.0.0.1`


# How to Use?
Just copy this command and paste it in your terminal then hit enter to initiate.
That's all. Now you just need to chill!
```
wget --no-check-certificate https://raw.githubusercontent.com/risfat/DevStack/main/devstack.sh -O devstack.sh;chmod +x devstack.sh;sh devstack.sh;rm -f devstack.sh
```

>If "`wget: Command not found`" appeared, then run the following command and rerun the previous command.

For Debian/Ubuntu based distro:
```
sudo apt-get install wget
```

You can also download the zip file from `Code` section or `release` section and extract them to Home directory. Then make `devstack.sh` executable by running `chmod +x devstack.sh` and execute `devstack.sh` on terminal by running `sh devstack.sh`.
Boom! all done! Pilot will make you fly soon! :p

>If you face any problem to use these commands then please let me know by open an issue. I'll help you, if there any unknown error appeared! 

## Thank you For Executing DevStack.
