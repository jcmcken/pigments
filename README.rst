Pigments
--------

The ``pigments`` library is a tiny library for colorizing console text in ANSI terminals.

This library derives wholly from the Fabric_ project, whose source can be found here_. It's main intention is to allow users to utilize Fabric's colorizing API without having to install Fabric. 

Usage is simple::

    from pigments import red, green

    print red('This is red') + ' ' + green('and this is green')

.. _Fabric: http://fabfile.org
.. _here: http://github.com/fabric/fabric
