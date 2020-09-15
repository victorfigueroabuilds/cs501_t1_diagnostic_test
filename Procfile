web: gunicorn manage:app
release: python manage.py db upgrade
heroku ps:scale web=1


