.. _intro:

Introduction
============

**XlsxWriter** is a Python module for writing files in the Excel 2007+ XLSX
file format.

It can be used to write text, numbers, and formulas to multiple worksheets and
it supports features such as formatting, images, page setup, autofilters,
conditional formatting and many others.

This module cannot be used to modify or write to an existing Excel XLSX file.
There are some :ref:`alternatives` Python modules that do that.

XlsxWriter is written by John McNamara who also wrote the perl modules
`Excel::Writer::XLSX <http://search.cpan.org/~jmcnamara/Excel-Writer-XLSX/>`_
and
`Spreadsheet::WriteExcel <http://search.cpan.org/~jmcnamara/Spreadsheet-WriteExcel/>`_
and who is the maintainer of
`Spreadsheet::ParseExcel <http://search.cpan.org/~jmcnamara/Spreadsheet-ParseExcel/>`_.
The XlsxWriter module is a port of Excel::Writer::XLSX. See :ref:`ewx`
for a list of currently ported features.



XlsxWriter is intended to have a high degree of compatibility with files
produced by Excel. In most cases the files produced are 100% equivalent to
files produced by Excel and the
`test suite <https://github.com/jmcnamara/XlsxWriter/tree/master/xlsxwriter/test/comparison>`_
contains a large number of test cases that verify the output of XlsxWriter
against actual files created in Excel.

XlsxWriter is licensed under a BSD :ref:`License` and is available as a ``git``
repository on `GitHub <http://github.com/jmcnamara/XlsxWriter>`_.
