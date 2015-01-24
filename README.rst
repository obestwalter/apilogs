awslogs
=======

.. image:: https://badge.fury.io/py/awslogs.png
    :target: http://badge.fury.io/py/awslogs

.. image:: https://pypip.in/d/awslogs/badge.png
    :target: https://crate.io/packages/awslogs/


awslogs is a simple command line tool to query `Amazon CloudWatch <http://aws.amazon.com/cloudwatch/>`_ logs::

    $ awslogs get /var/log/syslog *

* The latest documentation is available at: http://awslogs.readthedocs.org
* Installation instructions: http://awslogs.readthedocs.org/en/latest/installation.html

Features
--------

* Aggregate logs from accross streams and groups.
  * Aggregate all stream in a group.
  * Aggregate streams matching specific queries.
  * Filter both groups and streams using regular expressions.
* Colored output
* List existing groups
* List existing streams

Example
-------

tbc

Contribute
-----------

* Fork the repository on GitHub.
* Write a test which shows that the bug was fixed or that the feature works as expected.

  - Use ``python setup.py test``

* Send a pull request and bug the maintainer until it gets merged and published. :) Make sure to add yourself to AUTHORS.


Helpful Links
-------------

* http://aws.amazon.com/cloudwatch/
* http://boto.readthedocs.org/en/latest/ref/logs.html