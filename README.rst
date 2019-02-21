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
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-pipack/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pipack
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/kodexp/python-pipack.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/kodexp/python-pipack

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/kodexp/python-pipack?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/kodexp/python-pipack

.. |requires| image:: https://requires.io/github/kodexp/python-pipack/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/kodexp/python-pipack/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/kodexp/python-pipack/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/kodexp/python-pipack

.. |codecov| image:: https://codecov.io/github/kodexp/python-pipack/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/kodexp/python-pipack

.. |version| image:: https://img.shields.io/pypi/v/pipack.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pipack

.. |commits-since| image:: https://img.shields.io/github/commits-since/kodexp/python-pipack/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/kodexp/python-pipack/compare/v0.0.1...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pipack.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pipack

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pipack.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pipack

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pipack.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pipack


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install pipack

Documentation
=============


https://python-pipack.readthedocs.io/


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
