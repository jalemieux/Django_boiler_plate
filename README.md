# README #

Don't forget to set up a python venv and install django. Then create your app: 

project: 

    django-admin startproject mysite

    python manage.py runserver

package:

    python manage.py startapp polls


    python manage.py migrate


     sqlite3 db.sqlite3

create models in polls/models.py...
 
add pollsConfig to mysite/settings.py installed_app... Then reate migration files:

   python manage.py makemigrations polls

display migration: 

    python manage.py sqlmigrate polls 0001

execute migration: 

    python manage.py migrate
