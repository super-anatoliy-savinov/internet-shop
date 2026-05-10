web: gunicorn myshop.wsgi:application --workers 1 --threads 2
worker: celery -A myshop worker -l info --concurrency 1
