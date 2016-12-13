========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codacy| |codeclimate|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-machinelearning/badge/?style=flat
    :target: https://readthedocs.org/projects/python-machinelearning
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/thecontinium/python-machinelearning.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/thecontinium/python-machinelearning

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/thecontinium/python-machinelearning?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/thecontinium/python-machinelearning

.. |requires| image:: https://requires.io/github/thecontinium/python-machinelearning/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/thecontinium/python-machinelearning/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/thecontinium/python-machinelearning/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/thecontinium/python-machinelearning

.. |codecov| image:: https://codecov.io/github/thecontinium/python-machinelearning/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/thecontinium/python-machinelearning

.. |landscape| image:: https://landscape.io/github/thecontinium/python-machinelearning/master/landscape.svg?style=flat
    :target: https://landscape.io/github/thecontinium/python-machinelearning/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/thecontinium/python-machinelearning
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/thecontinium/python-machinelearning/badges/gpa.svg
   :target: https://codeclimate.com/github/thecontinium/python-machinelearning
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/machinelearning.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/machinelearning

.. |downloads| image:: https://img.shields.io/pypi/dm/machinelearning.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/machinelearning

.. |wheel| image:: https://img.shields.io/pypi/wheel/machinelearning.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/machinelearning

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/machinelearning.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/machinelearning

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/machinelearning.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/machinelearning

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/thecontinium/python-machinelearning/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/thecontinium/python-machinelearning/


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install machinelearning

Documentation
=============

https://python-machinelearning.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
