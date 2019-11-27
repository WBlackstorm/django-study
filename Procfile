web: sh -c 'cd application && python manage.py makemigrations'
web: sh -c 'cd application && python manage.py migrate'
web: sh -c 'cd application && gunicorn application.wsgi'
