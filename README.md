1. Download requeirements (pip3 install requeirements.txt)
2. runserver (python manage.py runserver)
3. docker-compose up (running redis)
4. celery -A proj_name beat (running celery beat)
5. celery -A proj_name worker -l INFO (running celery)
