php_vm
======================
php_vm is a native bridge between Ruby and PHP.


Requirements
------
* php (sapi/embed)


Installation
------
	$ gem install php_vm


Install PHP (sapi/embed)
------
	$ git clone git://github.com/php/php-src.git
	$ cd php-src
	$ ./buildconf
	$ ./configure --prefix=/usr/local --enable-embed=shared --disable-cli --disable-cgi --without-pear
	$ make
	$ sudo make install


Examples
------
https://github.com/yoshida-eth0/ruby-php_vm/tree/master/sample
