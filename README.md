# `teamsearch`
Project description


# Project setup
First of all, you need to create python environment and install requirements.txt file there

Then setup database with appropriate user and  permissions.

Create _**local_settings.py**_ file alongside _**settings.py**_ for putting your local credentials here.
Put your  `SECRET_KEY` and `DATABASES` configurations in local_settings.py file.

`SECRET_KEY = 'your secret key here'`

Example for Postgres database:

`DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'databasename',
        'USER': 'username',
        'PASSWORD': 'password',
        'HOST': 'localhost',
        'PORT': 'yourport',
    }
}`