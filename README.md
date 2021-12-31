# Craete virtual enviroment
`virtualenv venv`
# activate virtual enviroment
`source venv/bin/activate`
# deactivate virtual enviroment
`deactivate`
# install specific Django version
`pip install django==3.1`
# check you are in virtual enviroment
`pip freeze`
# Create Django project
`django-admin startproject mysite`
# Create a new Django app
`django-admin startapp myapp`
# Run Django server
`python manage.py runserver`
127.0.0.1.8000

# problem with django
  cors headers are not allowed in the response

  # django-cors-headers
  #
  # Django-Cors-Headers is a Django application that allows you to add CORS headers to your Django views.
  #
  # It is a fork of the Django-Cors-Middleware project.
# solution
`pip install django-cors-headers`
# add cors headers to your views
`from corsheaders.middleware import CorsMiddleware`
`from corsheaders.middleware import CorsMiddleware`
`CORS_ORIGIN_ALLOW_ALL = True`
`CORS_ALLOW_CREDENTIALS = True`
`CORS_ORIGIN_WHITELIST = (
    'http://localhost:8000',
    'http://,
    'http://,
    'http://
)


# create static files
`python manage.py collectstatic`
# run server

# visit `localhost:8000` to see Django server running

# how to do
laod static files
{% load static %} in teh html file in templates 
