# DjangoAddMySqlDB
Day-2 Adding mysql database and users 

Always run django-admin startproject projectname 

and Then

Create virtualenv and then activate 

Then run manage.py 
(To start Server) 

python manage.py runserver

(To create DB tables and start DB)

python manage.py migrate 
https://github.com/sumant039/DjangoAddMySqlDB.git

For Django Mysql Setup

mysqlclient or MySQL-python django missing 
Solution: 
Execute below cmd:
apt-get install python3-mysqldb libmysqlclient-dev python-dev



#After adding admin and user in Django web

mysql -u root
#use mysql database

use mysql 
select * from auth_user;



