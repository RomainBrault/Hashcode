.. -*- mode: rst -*-

.. |Travis| image:: https://travis-ci.com/RomainBrault/Hashcode.svg?token=BGkmfYrnrsiGdq17pxis&branch=master
.. _Travis: https://travis-ci.com/RomainBrault/Hashcode

.. |Python36| image:: https://img.shields.io/badge/python-3.6-blue.svg
.. _Python36: https://github.com/RomainBrault/Hashcode

Hashcode |Travis|_ |Python36|_
========

Hashcode qualification 2017. https://hashcodejudge.withgoogle.com/#/home. Score: 2500394

Environment
===========

Create conda environement::

    conda create -n hashcode python=3 anaconda numpy scipy ipython scikit-learn

Activate environment::

    source activate hashcode

Install
=======

Install hashcode::

    python setup.py develop

Usage
=====

Run program::

    python sample/main.py

Or::

    chmod +x run
    ./run
