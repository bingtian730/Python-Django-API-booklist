1. Create a empty folder called 'booklist'
2. cd booklist 
3. pipenv install django
4. pipenv shell 
5. django-admin startproject BookList .
6. python manage.py startapp BookListAPI
7. pipenv install djangorestframework
8. open the settings.py in folder 'BookList', add 'rest_framework', 'BookListAPI' into the installed_apps
9. add code in view.py 
10. create a file url.py inside BookListAPI folder and add code 
11. update code in url.py inside BookList folder 
12. python manage.py migrate 
13. python manage.py runserver
