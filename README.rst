Overview/ Readme
================

:Name: cysofa
:Website:
:Author: Matthew Turnock
:Version: 0.1



This Python package is a simple wrapper for a number of sofa subroutines. For a full list of supported subroutines see the API Reference.

.. image:: 
   :align: center

Documentation
-------------

Complete documentation can be found **Add link to site when complete**


Requirements
------------

this package requires the following Python packages:

* NumPy, for basic numerical routines
* Cython, required for building extensions

this package is usually tested on Linux

==============  ============  ===================
Platform        Site          Status
==============  ============  ===================
Linux           CircleCI      deD

==============  ============  ===================

Installation
------------
**UPDATE THIS SOON**
* Clone the github repository to your desired system location
* Download the sofa C distribution from http://www.iausofa.org
* Locate the sofa makefile in directory "sofa_c-20180130/sofa/20180130/c/src"
* Change line 52 in the makefile which currently reads:

::

 INSTALL_DIR = $(HOME)

to

::

 INSTALL_DIR = **cysofa-install-directory**/cysofa/src/cysofa/cypyx/cylib

* Run the sofa makefile as instructed by sofa documentation
* Navigate to your cysofa installation directory (where the makefile is located) and run the makefile. This will build and install cysofa into your python library.

License
-------

this package is released under the MIT license, hence allowing commercial
use of the library. Please refer to the LICENSE file.

FAQ
---

