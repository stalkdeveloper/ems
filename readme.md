# Employee Management System (EMS) with Django

Welcome to the Employee Management System (EMS) project built with Django. This project provides a web-based solution for managing employee records, including adding, viewing, and managing employee information.

## Features

- **Employee Management**: Create, read, update, and delete employee records.
- **User Authentication**: Secure login and management of employee data.
- **Responsive Design**: Accessible and user-friendly interface.


# `install command`
    1. django-admin startproject ems-django
    2. python manage.py startapp employees(or based on the file) 




# `comman command to run the project`
1. python manage.py runserver
2. python manage.py createsuperuser


python manage.py makemigrations
python manage.py migrate

root/
    ems_django/
        __init__.py
        settings.py
        urls.py
        wsgi.py
    employees/
        __init__.py
        admin.py
        apps.py
        models.py
        tests.py
        urls.py
        views.py
        templates/
            employees/
                index.html
    manage.py
