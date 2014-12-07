FROM ubuntu:14.04

MAINTAINER Oskar Maier, Dirk Fortmeier :version 0.1

RUN apt-get update
RUN apt-get install -y python2.7 ipython
RUN apt-get install -y python-pip python-numpy python-scipy libboost-python-dev build-essential
RUN pip install nibabel pydicom medpy

