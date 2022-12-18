namesfr
=====

Random french name generator


Usage
-----

Names can be used as a command line utility or imported as a Python package.

Command Line Usage
~~~~~~~~~~~~~~~~~~
To use the script from the command line:

.. code-block:: bash

    $ namesfr
    John Powell

Python Package Usage
~~~~~~~~~~~~~~~~~~~~
Here are examples of all current features:

.. code-block:: pycon

    >>> import namesfr
    >>> namesfr.get_full_name()
    u'Aurélien Germond'
    >>> names.get_full_name(gender='male')
    u'Frédéric Castan'
    >>> names.get_first_name()
    'Thierry'
    >>> names.get_first_name(gender='female')
    'Iris'
    >>> names.get_last_name()
    'Faust'


License
-------

This project is released under an `MIT License`_.

Data in the following files are public domain (governement data source 2018):

- dist.all.last
- dist.female.first
- dist.male.first

.. _mit license: http://th.mit-license.org/2013
