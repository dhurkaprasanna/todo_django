# todo_django
Steps To start a new Django Project:
1) Create a virtual Environment
2) Start new Django project: django-admin startproject todo
3) cd into the folder
4) to run the server: python manage.py runserver (here its not running because of virtual environment).
5) to migrate the first time: python manage.py migrate
6) to create the super user: python manage.py createsuperuser
7) here username is dhurkaprasanna and password is abc123
8) create an app: python manage.py startapp tasks
9) to migrate from the beginning: python manage.py makemigrations and then python manage.py migrate
