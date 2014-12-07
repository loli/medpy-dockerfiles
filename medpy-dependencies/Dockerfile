#####
# Dockerfile for MedPy - Medical image processing in Python
# https://pypi.python.org/pypi/MedPy/
# https://github.com/loli/medpy
#
# Docker container with MedPy dependencies, recommendations and graph-cut dependencies based on Ubuntu.
# version   0.1
# created   2014-12-07
#####

FROM ubuntu:14.04

MAINTAINER Oskar Maier <oskar.maier@googlemail.com>, Dirk Fortmeier

# get Ubuntu up-to-date
RUN apt-get update
RUN apt-get upgrade -y

# install MedPy depenencies
RUN apt-get install -y python2.7 
RUN apt-get install -y python-pip python-numpy python-scipy
RUN pip install nibabel pydicom

# install graph-cut functionality dependencies
RUN apt-get install -y libboost-python-dev build-essential

# install ipython
RUN apt-get install -y ipython


