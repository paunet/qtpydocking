**DEPRECATED** 

Qt-Advanced-Docking-System provides a Python wrapper directly, implemented with sip.
It's easily available through conda-forge, and you should use it instead of qtpydocking:

https://github.com/conda-forge/pyqtads-feedstock/#installing-pyqtads

**DEPRECATED** 


.. image:: https://img.shields.io/travis/klauer/qtpydocking.svg
        :target: https://travis-ci.org/klauer/qtpydocking

.. image:: https://img.shields.io/pypi/v/qtpydocking.svg
        :target: https://pypi.python.org/pypi/qtpydocking

===============================
qtpydocking
===============================

Pure Python port of the `Qt-Advanced-Docking-System <https://github.com/githubuser0xFFFF/Qt-Advanced-Docking-System>`_,
supporting PyQt5 and PySide through `qtpy <https://github.com/spyder-ide/qtpy>`_.

Requirements
------------

* Python 3.6+
* qtpy
* PyQt5 / PySide


Documentation
-------------

`Sphinx-generated documentation <https://klauer.github.io/qtpydocking/>`_


Installation
------------
::

   $ conda create -n docking -c conda-forge python=3.6 pyqt qt qtpy
   $ conda activate docking
   $ git clone https://github.com/klauer/qtpydocking
   $ cd qtpydocking
   $ python setup.py install

Running the Tests
-----------------
::

   $ python run_tests.py
