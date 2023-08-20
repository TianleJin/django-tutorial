# Django-Tutorial
A tutorial from the official Django documentation.

### Creating A Project
> django-admin startproject [project name]

### Running The Development Server
> python manage.py runserver [port number]

### Creating An App
> python manage.py startapp [app name]

### Migrating An App
> python manage.py makemigrations [app name]
> python manage.py sqlmigrate [app name] [migration name]
> python manage.py migrate

### Creating A Superuser
> python manage.py createsuperuser

### Running Tests For Apps
> python manage.py test [app name]

### Finding Django Documentation
> python -c "import django; print(django.__path__)"
