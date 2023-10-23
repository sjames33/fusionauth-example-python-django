
Run virtualenv for this project: fusionauth-example-python-django_BAK

Projects/Udacity/FSND-Virtual-Machine/vagrant/fusionauth-example-python-django_BAK

https://github.com/FusionAuth/fusionauth-example-python-django

https://fusionauth.io/blog/2020/07/14/django-and-oauth/ 

Somehow this got installed in the vagrant dir. 
Should be in the project dir.
--------------------------

In: Projects/Udacity/FSND-Virtual-Machine/vagrant/fusionauth-example-python-django_BAK

*  `source ../sb-env/bin/activate`


## Setup

*  `virtualenv sb-env`
*  `source sb-env/bin/activate`
*  `pip3 install django dateparser fusionauth-client pkce`
*  `pip3 install python-dotenv`   (added by sjames)
*  `django-admin startproject secretbirthdays`
*  `cd secretbirthdays`
*  `python3 manage.py startapp secretbirthdaysapp`
*  `python3 manage.py makemigrations`
*  `python3 manage.py migrate`
*  `python3 manage.py runserver`


