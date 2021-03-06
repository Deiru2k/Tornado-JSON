.. contents::
   :depth: 3
..

Tornado-JSON
============

|Build Status| |PyPI version| |Coverage Status| |Stories in Ready|

Overview
--------

Tornado-JSON is a small extension of
`Tornado <http://www.tornadoweb.org/en/stable/>`__ with the intent of
providing the tools necessary to get a JSON API up and running quickly.

Some of the key features the included modules provide:

-  Input and output **`JSON Schema <http://json-schema.org/>`__
   validation** by decorating RequestHandlers with ``@schema.validate``
-  **Automated route generation** with ``routes.get_routes(package)``
-  **Automated
   `GFM <https://help.github.com/articles/github-flavored-markdown>`__-formatted
   API documentation** using schemas and provided descriptions
-  **Standardized JSON output** using the
   **`JSend <http://labs.omniti.com/labs/jsend>`__** specification

Getting Started/FAQ
-------------------

**How do I use this thing?**

-  Check out the `Hello World
   demo <https://github.com/hfaran/Tornado-JSON/tree/master/demos/helloworld>`__
   for a quick example and the `accompanying
   walkthrough <http://tornado-json.readthedocs.org/en/latest/using_tornado_json.html>`__
   in the documentation. And then `**explore Tornado-JSON on readthedocs
   for the
   rest!** <http://tornado-json.readthedocs.org/en/latest/index.html#>`__

**Okay, but how do I install it?**

-  For the possibly stable

::

    pip install Tornado-JSON

-  For the latest and greatest

::

    git clone https://github.com/hfaran/Tornado-JSON.git
    cd Tornado-JSON
    sudo python setup.py install

**Neat, but ``x`` sucks, ``y`` is ugly, and ``z`` could be better.**

-  You would be awesome for `opening an issue about
   it <https://github.com/hfaran/Tornado-JSON/issues/new>`__, and I'll
   promise my best to take a look.

**You completely changed the interface in a recent update; what gives?**

-  But newer is so much better! Seriously though, ``Tornado-JSON`` is,
   at the moment, still very much a work in progress. Updates will be
   made that will break the existing interface (and replace it with a
   shiny, new, much better one). All in the name of making it better!
   (And progress etc.)

Dependencies
------------

*Python2.7 and Python3.3 are supported.*

These dependencies can be satisfied by running
``pip install -r requirements.txt``

-  `tornado <http://www.tornadoweb.org/en/stable/>`__
-  `jsonschema <https://python-jsonschema.readthedocs.org/en/latest/>`__

.. |Build Status| image:: https://travis-ci.org/hfaran/Tornado-JSON.png?branch=master
   :target: https://travis-ci.org/hfaran/Tornado-JSON
.. |PyPI version| image:: https://badge.fury.io/py/Tornado-JSON.png
   :target: http://badge.fury.io/py/Tornado-JSON
.. |Coverage Status| image:: https://coveralls.io/repos/hfaran/Tornado-JSON/badge.png
   :target: https://coveralls.io/r/hfaran/Tornado-JSON?branch=master
.. |Stories in Ready| image:: https://badge.waffle.io/hfaran/Tornado-JSON.png?label=In_Progress
   :target: http://waffle.io/hfaran/Tornado-JSON
