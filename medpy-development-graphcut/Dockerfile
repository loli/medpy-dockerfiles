# Build a Docker container that contains a python 2.7 
# environment and the recent MedPy development version
# build from source
#
#   docker build -t medpy-development-graphcut PATH_TO_THIS_FILE
#
#   docker run -ti medpy-development-graphcut

FROM ubuntu:14.04

MAINTAINER Oskar Maier, Dirk Fortmeier :version 0.1

RUN apt-get update
RUN apt-get install -y python2.7 ipython
RUN apt-get install -y python-pip python-numpy python-scipy libboost-python-dev build-essential
RUN pip install nibabel pydicom 

RUN apt-get install -y git
RUN mkdir /root/medpy
RUN cd /root/medpy
RUN git clone https://github.com/loli/medpy.git /root/medpy
RUN cd /root/medpy && python setup.py develop
