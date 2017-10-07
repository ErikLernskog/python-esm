========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |coveralls| |codecov|
        | |landscape| |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-esm/badge/?style=flat
    :target: https://readthedocs.org/projects/python-esm
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/ErikLernskog/python-esm.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ErikLernskog/python-esm

.. |requires| image:: https://requires.io/github/ErikLernskog/python-esm/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ErikLernskog/python-esm/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/ErikLernskog/python-esm/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/ErikLernskog/python-esm

.. |codecov| image:: https://codecov.io/github/ErikLernskog/python-esm/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/ErikLernskog/python-esm

.. |landscape| image:: https://landscape.io/github/ErikLernskog/python-esm/master/landscape.svg?style=flat
    :target: https://landscape.io/github/ErikLernskog/python-esm/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/ErikLernskog/python-esm
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/ErikLernskog/python-esm/badges/gpa.svg
   :target: https://codeclimate.com/github/ErikLernskog/python-esm
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/esm.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/esm

.. |commits-since| image:: https://img.shields.io/github/commits-since/ErikLernskog/python-esm/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ErikLernskog/python-esm/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/esm.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/esm

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/esm.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/esm

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/esm.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/esm


.. end-badges

esm

* Free software: BSD license

Installation
============

::

    pip install esm

Documentation
=============

https://python-esm.readthedocs.io/

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
