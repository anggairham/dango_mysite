# Belajar Django
* Django version 14.2
* Python version 3.x
* https://docs.djangoproject.com/en/4.2/intro/tutorial01/

* Jangan menamakan projek dengan **django** atau **test**
```
django-admin startproject mysite
```

### Run Python Server
* Jika di vps menggunakan Nginx dan Gunicorn uWSGI
* Menaruh projek django jangan di **/var/www/** bisa ditaruh di **/home/mystie/**
* https://serverfault.com/questions/331256/why-do-i-need-nginx-and-something-like-gunicorn
* https://www.rumahweb.com/journal/cara-install-django-python-di-vps-ubuntu/

* di local sudah ada runserver
```
py manage.py runserver
atau
py manage.py runserver 8080
atau
py manage.py runserver 0.0.0.0:8080
```

### Project VS apps
* What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

* Install App
```
py manage.py startapp polss
```
