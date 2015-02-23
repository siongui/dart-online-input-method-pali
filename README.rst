============================================
Dart Online Input Method - Pali (Pāli, Pāḷi)
============================================

Inspired by `palipad <https://code.google.com/p/palipad/>`_
(`demo of palipad <http://palipad.googlecode.com/git/palipad.html>`_),

Usage
=====

1. Development environment is ``Ubuntu 14.10`` and ``Dart 1.8``.

2. Download and install `Dart <https://www.dartlang.org/>`_.

3. Modify the first line in Makefile to point to the location
   of your unzipped Dart directory. For example, your unzipped
   Dart dir is located at ``../dart``, you should set the first
   line like this:

   .. code-block:: Makefile

     DART_DIR=../dart

4. Run the demo (with Dartium_):

   .. code-block:: bash

     $ make

4. Convert Dart code to JavaScript:

   .. code-block:: bash

     $ make js

Demo
====

See `project page <http://siongui.github.io/dart-online-input-method-pali/>`_.


UNLICENSE
=========

Released in public domain. See `UNLICENSE <http://unlicense.org/>`_.

.. _Dartium: https://www.dartlang.org/tools/dartium/
