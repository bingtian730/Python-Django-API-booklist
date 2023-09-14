# Python-Django-API-booklist
Create a empty folder called 'booklist'
cd booklist
pipenv install django
pipenv shell
django-admin startproject BookList .
python manage.py startapp BookListAPI
pipenv install djangorestframework
open the settings.py in folder 'BookList', add 'rest_framework', 'BookListAPI' into the installed_apps
add code in view.py
create a file url.py inside BookListAPI folder and add code
update code in url.py inside BookList folder
python manage.py migrate
python manage.py runserver
