# Build a Docker container that contains a python 2.7 
# environment and MedPy 0.2.2. with graphcut support
#
#   docker build -t medpy-r0.2.2-graphcut PATH_TO_THIS_FILE
#
#   docker run -ti medpy-r0.2.2-graphcut

FROM ubuntu:14.04

MAINTAINER Oskar Maier, Dirk Fortmeier :version 0.1

RUN apt-get update
RUN apt-get install -y python2.7 ipython
RUN apt-get install -y python-pip python-numpy python-scipy libboost-python-dev build-essential
RUN pip install nibabel pydicom medpy

