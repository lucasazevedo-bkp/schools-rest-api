# Schools REST API
> Courses, Avaliations and Authentication REST API.
>
> [Course](https://www.udemy.com/course/criando-apis-rest-com-django-rest-framework-essencial) & [Certificate](https://ude.my/UC-d18daeea-03fb-44f8-aa5e-383cbb49ac19)

![Ubuntu Version](https://img.shields.io/badge/ubuntu-20.04-blue)
![Python Version](https://img.shields.io/badge/python-3.8.10-blue)
![SQLite Version](https://img.shields.io/badge/sqlite-3.x-blue)
![Django Version](https://img.shields.io/badge/django-3.2.12-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Installation

Add an ".env" file and fill in the variables:

```sh  
# .env content
# for example, DJANGO_SECRET_KEY=hashed_secret_key
DJANGO_SECRET_KEY=
```

Install the requirements, run: migrations, server and create superuser to access /admin:

```sh
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
