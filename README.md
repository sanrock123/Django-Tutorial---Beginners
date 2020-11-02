# Django-Tutorial---Beginners
Will help you to understand the basic steps to learn basic Django ORM

Step 1: Installing Python

$ python
Python 2.7.5 (default, Jun 17 2014, 18:11:42)
[GCC 4.8.2 20140120 (Red Hat 4.8.2-16)] on linux2

Step 2: Installing Django

You can download the latest version of Django from the link http://www.djangoproject.com/download.

$ tar xzvf Django-x.xx.tar.gz
$ cd Django-x.xx
$ sudo python setup.py install

You can test your installation by running this command −

$ django-admin.py --version

Check the Path after installation in folder: C:\Python34\;C:\Python34\Lib\site-packages\django\bin\ in it, of course depending on your Python version.

cmd:
c:\>cd c:\Django-x.xx
c:\Django-x.xx>python setup.py install
c:\>python -c "import django; print(django.get_version())"
c:\> python
>>> import django
>>> django.VERSION

Step 3: Database Setup
Django supports several major database engines and you can set up any of them based on your comfort.

* MySQL (http://www.mysql.com/)
* PostgreSQL (http://www.postgresql.org/)
* SQLite 3 (http://www.sqlite.org/)
* Oracle (http://www.oracle.com/)
* MongoDb (https://django-mongodb-engine.readthedocs.org)
* GoogleAppEngine Datastore (https://cloud.google.com/appengine/articles/django-nonrel)

Step 4: Web Server

Create a Project:

Whether you are on Windows or Linux, just get a terminal or a cmd prompt and navigate to the place you want your project to be created, then use this code −

$ django-admin startproject myproject

