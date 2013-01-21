A LessCSS Compiler in Python
============================

LESS is an extension of CSS. You can write LESS code just like you would write
CSS, except you need to compile it to CSS. That's what the package is for. 

Installation
------------

Download and extract the distribution and then from the command prompt type::

    $ python setup.py install

Using from the command-line
---------------------------

Command line tool is called `lessc.py`, and is used like this::

    $ lessc.py source [destination]

The source is the LESS file you want to compile, and the destination is the
(optional) CSS file you want to compile it to::

    $ lessc.py style.less style.css

If you did't specify a destination, `lessc.py` will output to stdout::

    $ lessc.py style.less

Project status
--------------

Probably full of bugs with "potentially" all features apart from namespaces and
accessors.

Currently this has all the features that I require, but lacks full
compatibility with LessCSS_.


.. _LessCSS: http://lesscss.org/
.. vim: filetype=rst
