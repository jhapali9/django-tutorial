# django-tutorial

# Day 1
### Step 1 (setup and installation)
- check if python installed
- if not, install from python.org
```
python --version or python3 --version
```

- create and activate virtual environemnt
```
python3 -m venv test // create
source test/bin/activate // activate (Linux)
test\Scripts\activate // activate (Windows)
```
- install Django and check installation
```
pip install django (install)
django-admin --version (check)
````
### Step 2 — Create a Django Project
- start project
- first create a folder say django-tutorial 
```
django-admin startproject mysite django-tutorial
```
- above command creates django project called mysite within django-tutorial folder

- folder structure will be like this
```
myproject/
   manage.py        # Command-line utility
   myproject/
      __init__.py
      settings.py   # Project settings
      urls.py       # URL routing
      asgi.py       # ASGI server config
      wsgi.py       # WSGI server config
```

- Run development server
```
python manage.py runserver
```
- Open: http://127.0.0.1:8000 — you should see Django’s welcome page.



