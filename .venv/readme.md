
python -m venv .venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.\.venv\Scripts\activate.ps1
python.exe -m pip install --upgrade pip
python -m pip install djang
 django-admin startproject django_project .
 python manage.py startapp accounts
 python -m pip install whitenoise
 python manage.py runserver
