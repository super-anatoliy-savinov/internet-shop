web: gunicorn myshop.wsgi:application --bind 0.0.0.0:$PORT --workers 1 --threads 2
worker: celery -A myshop worker -l info --concurrency 1
