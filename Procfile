web: export FLASK_APP=project.server && export APP_SETTINGS="project.server.config.DevelopmentConfig" && flask db init && flask db migrate && flask db upgrade && flask run --host=0.0.0.0
heroku ps:scale web=1

