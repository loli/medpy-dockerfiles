#####
# Dockerfile for MedPy - Medical image processing in Python
# https://pypi.python.org/pypi/MedPy/
# https://github.com/loli/medpy
#
# Docker container building with the current MedPy release version found at PyPi.
# Includes the pre-compiled ITK bindings.
# version   0.1
# created   2014-12-07
#####

FROM loli/medpy:itk

MAINTAINER Oskar Maier <oskar.maier@googlemail.com>, Dirk Fortmeier

# install MedPy release version
RUN pip install medpy

