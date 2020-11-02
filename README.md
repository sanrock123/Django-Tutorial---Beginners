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

----> Create a Project:

Whether you are on Windows or Linux, just get a terminal or a cmd prompt and navigate to the place you want your project to be created, then use this code −

$ django-admin startproject myproject

This will create a "myproject" folder with the following structure −

myproject/
   manage.py
   myproject/
      __init__.py
      settings.py
      urls.py
      wsgi.py
      
$ python manage.py help

-----> Setting Up Your Project:

Your project is set up in the subfolder myproject/settings.py. Following are some important options you might need to set −

DEBUG = True

DATABASES = {
   'default': {
      'ENGINE': 'django.db.backends.sqlite3',
      'NAME': 'database.sql',
      'USER': '',
      'PASSWORD': '',
      'HOST': '',
      'PORT': '',
   }
}

Now that your project is created and configured make sure it's working −

$ python manage.py runserver
You will get something like the following on running the above code −

Validating models...

0 errors found
September 03, 2015 - 11:41:50
Django version 1.6.11, using settings 'myproject.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.




