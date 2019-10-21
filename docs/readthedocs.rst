Contributing to Website Documentation Guide
===========================================

The documentation for our website is located within the `docs <https://github.com/RichUng/dataconla-frontend/tree/master/docs>`_ directory of our git repository. When the master branch of this git repository is updated with a new commit, `Read the Docs <https://readthedocs.org/>`_ automatically builds and hosts the documentation within the docs folder to our `documentation site <https://dataconla-frontend.readthedocs.io/>`_. The `status of the documentation build <https://readthedocs.org/projects/dataconla-frontend/>`_ displays whether or not the documentation successfully builds on Read the Docs.



Helpful Links
-------------

- `Template Guide for reStructuredText syntax <https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/#id1>`_
- `reStructuredText Cheat Sheet <https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>`_

How to Create a New Documentation Site
--------------------------------------

Refer to the `Getting Started guide <https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html>`_ within the Read the Docs website, and refer to the above helpful links in order for syntax reference. Take a look at the Quick Start video for information about developing the documentation locally. Also, be sure to include a line that contains ``master_doc = 'index'`` within the *conf.py* file in order to successfully build on Read the Docs as mentioned `here <https://github.com/readthedocs/readthedocs.org/issues/2569>`_.