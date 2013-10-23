django template project with app for active directory login
====================

A starter project with bootstrapped forms, user authentication through active directory and debug-toolbar included! 

Example usage
=============

    $ virtualenv mysite-env --no-site-packages
    $ source mysite-env/bin/activate
    (mysite-env)$ pip install django
    (mysite-env)$ django-admin.py startproject --template=https://github.com/kl4us/django-ad-login/zipball/master mysite
    (mysite-env)$ cd mysite
    (mysite-env)$ pip install -r requirements.txt
    (mysite-env)$ python manage.py syncdb
    (mysite-env)$ python manage.py runserver

Hit http://127.0.0.1:8000 to view the site!