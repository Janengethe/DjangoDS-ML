* `pip install django`
* `python3 -m django --version`
* `mkdir myproject`
* `cd myproject`
* `django-admin startproject mywebapp`
* 
```
cd mysite
python3 -m venv venv
source venv/bin/activate
```
* `pip install django`

1. Create a new app for your main functionality:
`python3 manage.py startapp myapp`
2. Add the app to your settings:
```
# In settings.py

INSTALLED_APPS = [
    # ...
    'mywebapp',
]
```