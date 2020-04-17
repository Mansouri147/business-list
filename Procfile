web: gunicorn Business_list.wsgi --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate