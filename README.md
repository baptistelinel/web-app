# Web app

## Application aim

Provide an example of Flask application using Postgresql with Docker.

## Start application

Create containers web and database:
```
make start_app
```

Run migration scripts:
```
make run_migrations
```

The application is running on http://localhost:5000.

## Destroy application

```
make destroy_app
```

## Docker containers information

| Name  |Image  |Port   |
|---|---|---|
|web    |web-app_web |5000->5000/tcp |
|database   |web-app_database       |5432/tcp |

## Docker versions

* Docker version 19.03.8, build afacb8b
* docker-compose version 1.25.4, build 8d51620a
