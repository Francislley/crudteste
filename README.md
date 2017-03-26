# My very first application with Django

## Get started

### Use pip to install python-django and virtualenv(just for python 2.7)
### For python 3.x you can use venv (included into it) 


Here we gonna find some settings that are necessary to start with the project

1. Create a new folder that will store the Django project and the virtual enviroment
 `$ mkdir Django`

2. Create a new virtual enviroment
 `$ virtualenv entornovirtual` (python 2.7)
 `$ python -m venv entorno virtual` (python 3.x)


3. Activate the virtual enviroment
 `$ source entornovirtual/bin/activate`
 Use `$ deactivate` to turn off the virtualenv

4. With the virtualenv activate, we gonna install django
 `$ pip install django`

5. Finally we need to create a new django project
 `$ django-admin.py startproject commerce`

6. Starting the server
 `$ python manage.py runserver`

7. Creating a requirements.txt
`$ pip freeze > requirements.txt`

8. Using an existing requirements.txt
`$ pip install -r requirements.txt `

9. Making migrates
` $ python manage.py migrate`

10. Creating modules
`$ python manage.py startapp products`

11. Checking our code
`$ ./manage.py check`

12. We need to add or "install" each appliations into the settings.py

13. Creating migrations
`$ ./manage.py makemigrations`

14. Creating a superuser
`$ ./manage.py createsuperuser`


