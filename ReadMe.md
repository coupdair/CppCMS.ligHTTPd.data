on debian

# repository

## clone as user

~~~ { .bash }
cd
mkdir -p SC/CppCMS.lighttpd/
cd SC/CppCMS.lighttpd/
git clone git@github.com/coupdair/CppCMS.ligHTTPd.data data
~~~

## install as root

~~~ { .bash }
cd /var/www/html/
sudo rm -fr *
sudo git clone /home/$USER/SC/CppCMS.lighttpd/data
sudo mv data/.??* data/* .
sudo rmdir data
~~~
