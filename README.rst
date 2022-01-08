

Example Project
===============
This is an example project that is used to demonstrate how to publish
Python packages on PyPI. To take a look at the step by step guide on how to 
do so, make sure you read `my article on Towards Data Science <https://towardsdatascience.com/how-to-upload-your-python-package-to-pypi-de1b363a1b3>`_.

Installing
============

.. code-block:: bash

    pip install example-publish-pypi-medium

Usage
=====

.. code-block:: bash

    >>> from src.example import custom_sklearn
    >>> custom_sklearn.get_sklearn_version()
    '0.24.2'
