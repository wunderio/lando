PHP 8.0 FPM
===========

This is extending PHP 8.0 FPM image from
https://github.com/lando/php/blob/main/images/8.0-fpm/Dockerfile

On Dockerhub it's located at:
https://hub.docker.com/r/devwithlando/php/tags

Updating
---------

Make changes in the Dockerfile and run the Makefile with:

    make

Push to Docker Hub

    docker login
    make push
