===============================
Term Discovery Evaluation
===============================

DESCRIPTION

* Free software: GPLv3 license
* Extended to support phone-level segmentation eval


FREEZING

To build a frozen version::

  $ python setup.py build_ext --inplace
  $ python setup_freeze.py build_exe
  $ python move_build.py CORPUS OUTPUTDIR
