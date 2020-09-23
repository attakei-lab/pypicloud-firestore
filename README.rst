===================
pypicloud-firestore
===================

pypicloud cache implementation for Cloud Firestore.

Usage
=====

Install
-------

Currently, this package is hosting in attakei's personal PyPI.
To install, use extra index.

.. code-block::

   $ pip install pypicloud
   $ pip install pypicloud-firestore --extra-index-url https://pypi.attakei.net/simple/

Configuration
-------------

Set ``pypi.db = pypicloud_firestore.FirestoreCache`` to use it.
And set options.

* ``db.collection_name``: Firestore collection to store package data (default is ``pypicloud_packages`` )
