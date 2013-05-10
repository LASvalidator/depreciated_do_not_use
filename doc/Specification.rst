.. raw:: pdf

    SetPageCounter 1 arabic

.. footer::

   This document describes all of the checks that lasvalidate puts LAS files through.

   Page ###Page###

Date: 

initial draft created on May 10th, 2013

***************************************************************************************
 lasvalidate - a tool for validating LAS files
***************************************************************************************

.. class:: heading4
    
This document describes all of the checks that lasvalidate puts LAS files through.

==============================================================================
Introduction
==============================================================================

This document describes all of the checks that lasvalidate puts LAS files through.

==============================================================================
Header checks
==============================================================================

File Signature:
  The file signature must contain the four characters "LASF".

.. csv-table:: File Signature
    :widths: 70, 10, 10
    "char[4]", "must always equal 'LASF'", "fail"

Global Encoding:
  This is a bit field used to specify global properties about the file.

.. csv-table:: Global Encoding
    :widths: 70, 10, 10
    "char[4]", "must always equal 'LASF'", "fail"
