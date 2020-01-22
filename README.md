# RideshareBeta

Note: Create and source the following `env` file or else database connections wont work.

    export DB_HOST=localhost
    export DB_NAME=ridesharebeta
    export DB_USER=postgres
    export DB_PORT=5432
    export DATABASE_URL=postgres://$DB_USER@$DB_HOST:$DB_PORT/$DB_NAME
    export SECRET_KEY=some_secret_key
    export ENV=development # If this is "development" SSL is not required in settings.py

Note: You may also need to create a `superuser` for admin login:

    python manage.py createsuperuser
