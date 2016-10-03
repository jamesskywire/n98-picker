# n98-picker
Dynamically works out which version of n98-magerun to use for different Magento versions based on current directory.

Usage instructions
====================
1. Install n98-magerun and n98-magerun2 into /usr/local/bin
~~~
#install n98-magerun
wget https://files.magerun.net/n98-magerun.phar
chmod +x ./n98-magerun.phar
sudo cp ./n98-magerun.phar /usr/local/bin/

#install n98-magerun2
wget https://files.magerun.net/n98-magerun2.phar
chmod +x ./n98-magerun2.phar
sudo cp ./n98-magerun2.phar /usr/local/bin/
~~~
2. Install this script
~~~
chmod +x ./n98
ln -s $(pwd)/n98 /usr/local/bin/n98
~~~
3. Navigate to project root.
4. Run n98.

Updating
==========
1. Just git pull to get the latest version
 