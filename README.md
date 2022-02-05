# djangoCMS 4 Project

## Setup:

Create a virtual python envoirement:

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

Your can check our Installation for any erros with:

```bash
python manage.py cms check
```