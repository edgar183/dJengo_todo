# Django to do project. 

- sudo pip3 install django==1.11
Install Django LT support version

- django-admin startproject django_todo .
  -Start new project with name django_todo in root dir

- django-admin startapp todo
  - Start app in django project. the app have its own views. it is component to project.

- python3 manage.py runserver $IP:$C9_PORT
  - To start server. This commant can be added to .bash_aliases file alias run="python3 ~/workspace/manage.py runserver $IP:$C9_PORT"