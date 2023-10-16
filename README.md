# check python version
python --version
# create project django
django-admin startproject webbanhang
cd webbanhang
# create virtual environment python
python -m venv venv
code .
# active virtual environment python
source venv/bin/activate
# install something in virtual environment
pip install --upgrade pip
[] pip install  requests
[] pip freeze
# install package in file
[] pip install -r requiments.txt
# create module 
django-admin startapp app
# install Django in virtual env
python -m pip install Django
python manage.py migrate
# run app
python manage.py runserver
# create database
python manage.py makemigrations
python manage.py migrate
# install module supporting for upload image
pip install pillow
python -m pip install Pillow
# export database from sqllite3
python manage.py dumpdata > db-dump.json