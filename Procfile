web: sh -c 'cd application'
web: python manage.py makemigrations
web: python manage.py migrate
web: gunicorn application.wsgi
