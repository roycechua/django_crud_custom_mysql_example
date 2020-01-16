# django_crud_custom_mysql_example
This is a very simple CRUD application made with Django (not using the models) using instead custom raw SQL code using Django import connection library. 

## Pre-requisities
* Python 3 and Django (2 and above preferrably) must be installed on the machine locally.
* You need to run 
``` python
   pip install mysqlclient
```
to install the mysql client package
* XAMPP or MySQL stand-alone 
* Create the MySQL Database **testprojdb** with table *accounts* on MySQL with the following SQL Commands:
``` mysql 
  CREATE TABLE accounts(id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(50), email VARCHAR(50));
```
## Setup and Run
* Clone the repository 
* Run the the Django project from the terminal with the command 
``` python
  python manage.py runserver
```
