# Commards

django-admin startproject drfcommerce

python manage.py runserver

from django.core.management.utils import get_random_secert_key

print(get_random_secret_key())

pip freeze > requirements.txt

pip install python-dotenv

pip install djangorestframework

pip install pytest

pip install pytest-django

pip install flake8

python manage.py startapp product ./drfecommerce/product

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

pip install drf-spectacular

python manage.py spectacular --file schema.yml

pip install coverage

coverage run -m pytest

coverage html

pip install pytest-cov

pip install pytest-factoryboy