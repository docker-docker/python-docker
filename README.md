# python-docker

A slim base version image for python

# How to use this `Dockerfile`

```shell

$ docker build -f Dockerfile -t test:python .
$ docker run --name test -d -p 5000:5000 -v $PWD:/opt/app test:python

```