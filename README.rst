User documentation
==================

End-user documentation for eResearch Centre systems powered by Plone.

About this documentation
------------------------

* Powered by Sphinx
* Configuration-based documentation: an example of using conditional statments
  to build up documentation.  Just look for ``ifconfig`` sections and the
  example config in ``source/conf.py``.
* Branchable for different projects: just customise the screenshots and
  ``source/conf.py`` settings.

Install
-------

To install all dependencies and then build the actual documentation, do
the following::
  
    python boostrap.py
    ./bin/buildout
    ./bin/sphinxbuilder

To re-build the documentation, just run::

    ./bin/sphinxbuilder

The final path of the rendered documentation is described in the console 
output.
