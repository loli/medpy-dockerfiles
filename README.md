Dockerfiles for MedPy - Medical image processing in Python
==========================================================
**PyPi**: <https://pypi.python.org/pypi/MedPy/>
**GitHub**: <https://github.com/loli/medpy>
**DockerHub**: <https://registry.hub.docker.com/u/loli/medpy>
**Documentation**: <http://pythonhosted.org/MedPy/>

Description
-----------
Inter-dependent docker files to create out-of-the-box instances of **MedPy**. Intended for internal use, see <https://registry.hub.docker.com/u/loli/medpy> for pre-build containers, <https://pypi.python.org/pypi/MedPy/> for releases and <https://github.com/loli/medpy> for development version.

Dependencies-tree
-----------------

    * Ubuntu:14.04
        * loli/medpy:dependencies
            * loli/medpy:release
            * loli/medpy:development
            * loli/medpy:itk
                * loli/medpy:release-itk
                * loli/medpy:development-itk
                
Authors
-------
    
    * Oskar Maier <oskar.maier@googlemail.com>
    * Dirk Fortmeier

