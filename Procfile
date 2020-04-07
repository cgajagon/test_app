release: python manage.py migrate
web: gunicorn config.wsgi:application
<<<<<<< HEAD
worker: celery worker --app=config.celery_app --loglevel=info -B
=======
worker: celery worker --app=config.celery_app --loglevel=info
beat: celery --app=config.celery_app beat
>>>>>>> 1d65ff06a1a7241ca50ada2417e7b9742f34026a
