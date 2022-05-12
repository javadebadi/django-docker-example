#  Dockerized Django Project

This repository contains a django project with docker files and settings to run the project in a docker container with nginx server.

## Structure of the repository

Directoris and files to copy inside docker container for the project:

- djangoproject/ : top directory of django project that we have named it **djangoproject**
- requirements.txt : list of dependencies that needed to be installed in docker container to run our Python application
- nginx.default: settings of the nginx server which will be used to serve django application inside docker container
- start_server.sh: script to make start and run the nginx server inside the docker container

Files to build docker image and run docker container

- Dockerfile: the Dockerfile to build a docker image of the project

- run-docker: a command to run the docker container form the docker image that is built

- build-docker: a command you need to run to build the docker image from Dockefile


## Reference

I have build this repository by based on this link: [https://semaphoreci.com/community/tutorials/dockerizing-a-python-django-web-application]()
