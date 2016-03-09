Hi Friend This is Good Script For IT Assets Management.

I will Show you configure this setup easy.

First you knowledge about domain or hosting some php.

now you need download ampps its good software for local hosting server or for domain.

for download [click here](http://s1.softaculous.com/a/ampps/files/Ampps-xp-3.4-setup.exe)

after ampps installation you need enable some PHP extension.
1)php_openssl.dll
2)php_fileinfo.dll

after enable need install Composer.

Download composer [click here](https://getcomposer.org/Composer-Setup.exe)

Run Setup asking for path you need PHP path I have that path but depend on your ampps installation path.

C:\Program Files (x86)\Ampps\php\php.exe

Now Composer Setup Done.

Now Copy Snipe-IT All File in ampps root (www) folder.

after that need open command prompt

goto snipe folder path and hit this command

composer install

then its download all dependency.

Now second command 

composer update

now you need to configure database in phpadmin

Kindly Check this database.php

C:\Users\Karan\Documents\GitHub\Snipe-IT\app\config

Set your username and password

after all steps just final setup you need

php artisan app:install --env=production

asking for all name email just type it all done after this command 

for public access directory 

C:\rootpath\Snipe-IT\public

Need Any support Comment also I will add shortly video tutorial.



 
  


