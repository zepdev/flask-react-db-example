# Example web app with three services Flask, React, and Postgres

## Build the containers
docker-compose build

## Get things up and running
docker-compose up -d

### Create DB
docker-compose exec api python manage.py recreate_db

### Seed DB
docker-compose exec api python manage.py seed_db


Application is based on: https://testdriven.io/courses/auth-flask-react/
