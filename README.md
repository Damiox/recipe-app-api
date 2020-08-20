# recipe-app-api
Recipe app api source code for https://www.udemy.com/course/django-python-advanced/

## Build

The following command will build the docker image:
```
docker-compose build
```

## Run tests

The following command will run the set of unit tests along with the linting:
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

## Start the server

The following command will leave a container running so you can test the API through the Django Admin site:
```
docker-compose up
```
