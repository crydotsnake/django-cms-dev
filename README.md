# djangoCMS Boilerplate

## Setup:

Create a virtual python environment:

```bash
mkvirtualenv django-cms-dev
```

Or if you dont have virtualenvwrapper installed:

```bash
virtualenv django-cms-dev
```

## Install requirements

```bash
pip install -r requirements.txt
```

## Run the migrations

```bash
python manage.py migrate
```

## Create an admin user

```bash
python manage.py createsuperuser
```

## Start development server

```bash
python manage.py runserver
```

## Check your installation

Your can check your Installation for any erros with:

```bash
python manage.py cms check
```
