web: gunicorn --chdir project/server/ __init__:app
heroku ps:scale web=1
release: chmod u+x launch.sh && ./launch.sh

