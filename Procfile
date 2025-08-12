web: gunicorn "CTFd:create_app()" --worker-class gevent --workers 2 --timeout 120 --bind 0.0.0.0:$PORT
