#################
Contributor Guide
#################

.. toctree::
   :maxdepth: 2

.. index:: single: patches; contributing

Contributing Patches
====================

If you wish to contribute a patch, please open a `pull request`__ at GitHub.

__ https://help.github.com/articles/using-pull-requests

Contribution Guidelines
=======================

* Do your best to adhere to the existing coding conventions and idioms.
* Don't use hard tabs, and don't leave trailing whitespace on any line.
  Before committing, run ``git diff --check`` to make sure of this.
* Do document every function you add using `Doxygen`_ annotations.
  Read the `tutorial`_ or just look at the existing code for examples.
* Don't touch the :file:`VERSION` file. If you need to change it, do so on
  your private branch only.
* Do feel free to add yourself to the :file:`CREDITS` file and the
  corresponding list in the the :file:`README`. Alphabetical order applies.
* Don't touch the :file:`AUTHORS` file. If your contributions are
  significant enough, be assured we will eventually add you in there.

.. _Doxygen:  http://www.doxygen.org/
.. _tutorial: http://www.stack.nl/~dimitri/doxygen/manual/docblocks.html

Project Scope
=============

Before spending much time writing a large patch set that adds all the
features that a library ostensibly is missing, please take a moment to
consider whether the desired functionality truly fits within the stated
scope of the project.

Legal Considerations
====================

TODO
