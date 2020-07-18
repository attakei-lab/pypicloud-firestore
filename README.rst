===================
pypicloud-firestore
===================

pypicloud cache implementation for Cloud Firestore.


Usage
=====

Install
-------

.. code-block::

   $ pip install pypicloud
   $ pip install https://github.com/attakei-sandbox/pypicloud-firestore/archive/master.zip


Configuration
-------------

Set ``pypi.db = pypicloud_firestore.FirestoreCache`` to use it.
And set options.

* ``db.collection_name``: Firestore collection to store package data (default is ``pypicloud_packages`` )


