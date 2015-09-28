# phalcon.so for cPanel
- centos 6.6 kernel 2.6.32-504.23.4.el6.x86_64
- phalcon 2.0.8
- php 5.4.42
- php 5.5.27
- php 5.6.10

# Installation
- if your php version is smaller than 5.4 go to cPanel and look for "PHP Version Manager" or "ntPHPSelector" and set the desired version for your public directory of your phalcon project.
- copy the desired phalcon.so on your cPanel account
https://github.com/magnxpyr/phalcon.so/archive/php5.4.zip
https://github.com/magnxpyr/phalcon.so/archive/php5.5.zip
https://github.com/magnxpyr/phalcon.so/archive/master.zip

- add the extension in php.ini
```
extension=/path/to/phalcon.so
```