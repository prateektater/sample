# Sample

This is a simple vote app written in Django using the instructions given in the Django -> Documentation -> Tutorial

It includes basic concepts of database, testing and CI/CD using Travis CI and Docker.

## For Docker
check docker container with command
docker ps

copy the container id

open another terminal and write

docker exec -it "docker id" bash -l

and create a super user

python manage.py createsuperuser

Reference: https://docs.djangoproject.com/en/2.1/intro/tutorial01/
