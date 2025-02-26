First of all, create Virtual Environment
create: virtualenv venv or python3 -m venv venv
activate: source venv/bin/activate

then install Django in requirements.txt

pip install -r requirements.txt

after install checked by: django-admin --help

start project: django-admin startproject projectname 
for avoiding two folders in projectname we can use: django-admin startproject projectname .

<!-- now, goto settings.py -->

then create an app: ❯ todo django-admin startapp todo
when creating any app it is need to register in main settings.py.
find installed_APPS and then register our app.
'todo',
 
