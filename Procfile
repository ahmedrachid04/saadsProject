release: python manage.py migrate
web: gunicorn projet.wsgi --bind 0.0.0.0:$PORT
