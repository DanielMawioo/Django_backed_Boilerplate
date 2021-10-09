# Docker Compose _ Django _ PostgreSQL _ Redis & Celery Baseline Configuration.

## using python3 lightweight "alphine --version"

# Getting started on linux , windows remove {sudo } command.
- 1. sudo docker-compose build
- 2. sudo docker-compose run --rm app django-admin startproject {Your project name here} .
- 3. sudo docker-compose up

## open another terminal window. Leave the previus running the docker container.
- 4. docker exec -it django_app sh