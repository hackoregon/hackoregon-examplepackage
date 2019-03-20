=============================
hackoregon-examplepackage
=============================

.. image:: https://badge.fury.io/py/hackoregon-examplepackage.svg
    :target: https://badge.fury.io/py/hackoregon-examplepackage

.. image:: https://travis-ci.org/hackoregon/hackoregon-examplepackage.svg?branch=master
    :target: https://travis-ci.org/hackoregon/hackoregon-examplepackage

My project says hi

Documentation
-------------

The full documentation is at http://hackoregon.github.io/hackoregon-examplepackage

Quickstart
----------

Install hackoregon-examplepackage::

    pip install hackoregon-examplepackage

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'examplepackage.apps',
        ...
    )

Add hackoregon-examplepackage's URL patterns:

.. code-block:: python

    from examplepackage import urls as examplepackage_urls


    urlpatterns = [
        ...
        url(r'^', include(examplepackage_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
