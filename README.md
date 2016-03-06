#### pkleadjwebdev
#####14
######production using apache
```
sudo apt-get install apache2
sudo apt-get install libapache2-mod-wsgi
```
create a my.conf file. know some fields:  
/etc/apache2/sites-available  
```
ServerAdmin
ServerName
ServerAlias
WSGIScriptAlias
```

enable and disable conf file
```
a2ensite my.conf
a2dissite 000-default.conf
sudo service apache2 restart
```
