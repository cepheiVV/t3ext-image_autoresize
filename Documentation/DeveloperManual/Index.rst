﻿.. include:: ../Includes.rst.txt
.. _developer-manual:

Developer Manual
================

This chapter describes some internals of the Resize Images Automatically
extension to let you extend it easily.


Signals and Slots
-----------------

The concept of *signals* and *slots* allows for easy implementation of the
`Observer pattern <https://en.wikipedia.org/wiki/Observer_pattern>`_ in
software, something similar to *hooks* in former versions of TYPO3. Its
implementation in TYPO3 CMS has been backported from Flow, so please read
chapter
`Signals and Slots <https://flowframework.readthedocs.io/en/stable/TheDefinitiveGuide/PartIII/SignalsAndSlots.html>`_
from Flow official documentation. In short, *signals* are put into the code and
call registered *slots* when run through.

Available signals and slots:

.. toctree::
   :maxdepth: 2

   PostProcessingConfiguration
   PostProcessingImages
