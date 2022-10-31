FROM devwithlando/php:8.0-fpm-4

# Ppdates the package lists for upgrades for packages that need upgrading.
RUN apt-get update

# To be able to run ESLint with GrumPHP, we need Node.js on appserver.
apt-get install -y nodejs
