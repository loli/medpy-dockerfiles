#####
# Dockerfile for MedPy - Medical image processing in Python
# https://pypi.python.org/pypi/MedPy/
# https://github.com/loli/medpy
#
# Docker container with MedPy dependencies, recommendations and graph-cut dependencies based on Ubuntu.
# version   0.2
# created   2014-12-07
#####

FROM ubuntu:18.04

MAINTAINER Oskar Maier <oskar.maier@googlemail.com>, Dirk Fortmeier

# get Ubuntu up-to-date
RUN apt-get update
RUN apt-get upgrade -y

# install MedPy depenencies
RUN apt-get install -y python3.6
RUN apt-get install -y python3-pip

# install graph-cut functionality dependencies
RUN apt-get install -y libboost-python-dev build-essential
