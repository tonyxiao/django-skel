web: newrelic-admin run-program gunicorn -c gunicorn_config.py wsgi:application
scheduler: python manage.py celeryd -B -E --maxtasksperchild=1000
worker: python manage.py celeryd -E --maxtasksperchild=1000
