% prepara el repositorio para su despliegue. 
release: sh -c 'cd doc && cd decide && python manage.py migrate'
% especifica el comando para lanzar Decide
web: sh -c 'cd doc && cd decide && gunicorn decide.wsgi --log-file -'
