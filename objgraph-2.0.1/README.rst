Python Object Graphs
====================

.. image:: https://travis-ci.org/mgedmin/objgraph.svg?branch=master
   :target: https://travis-ci.org/mgedmin/objgraph
   :alt: Build Status

.. image:: https://coveralls.io/repos/mgedmin/objgraph/badge.svg?branch=master
   :target: https://coveralls.io/r/mgedmin/objgraph?branch=master
   :alt: Test Coverage

.. image:: https://pypip.in/version/objgraph/badge.svg?style=flat
   :target: https://pypi.python.org/pypi/objgraph

.. image:: https://readthedocs.org/projects/objgraph/badge/?version=latest
   :target: https://readthedocs.org/projects/objgraph/?badge=latest
   :alt: Documentation Status


``objgraph`` is a module that lets you visually explore Python object graphs.

You'll need `graphviz <http://www.graphviz.org/>`_ if you want to draw
the pretty graphs.

I recommend `xdot <http://pypi.python.org/pypi/xdot>`_ for interactive use.
``pip install xdot`` should suffice; objgraph will automatically look for it
in your ``PATH``.


Installation and Documentation
------------------------------

``pip install objgraph`` or `download it from PyPI
<http://pypi.python.org/pypi/objgraph>`_.

Documentation lives at http://mg.pov.lt/objgraph.


.. _history:

History
-------

I've developed a set of functions that eventually became objgraph when I
was hunting for memory leaks in a Python program.  The whole story -- with
illustrated examples -- is in this series of blog posts:

* `Hunting memory leaks in Python
  <http://mg.pov.lt/blog/hunting-python-memleaks.html>`_
* `Python object graphs
  <http://mg.pov.lt/blog/python-object-graphs.html>`_
* `Object graphs with graphviz
  <http://mg.pov.lt/blog/object-graphs-with-graphviz.html>`_


.. _devel:

Support and Development
-----------------------

The source code can be found in this Git repository:
https://github.com/mgedmin/objgraph.

To check it out, use ``git clone https://github.com/mgedmin/objgraph``.

Report bugs at https://github.com/mgedmin/objgraph/issues.
