## Install Docker

* [Mac](https://docs.docker.com/docker-for-mac/)
* OR...
* [Ubuntu](https://docs.docker.com/engine/installation/linux/ubuntu/)

## Dev 

* $ `docker build -t pythonapp:dev -f Dockerfile.dev .`           Don't forget the PERIOD

* $ `docker run --rm -v $(pwd):/home/x/syn/pythonapp pythonapp:dev`


## Prod 

* $ `docker build -t pythonapp:prod -f Dockerfile.prod .`            Don't forget the period

* $ `docker run --rm pythonapp:prod`

## Validation

* Should print 'hello' in the terminal.

## Refs

* http://odewahn.github.io/docker-jumpstart/building-images-with-dockerfiles.html