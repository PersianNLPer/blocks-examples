Neural Machine translation based on Blocks
===============

This repository contains scripts to train and test a neural machine translation system.
The code is forked from blocks-examples.
The fixes for saving/loading the models and translating a test set using an existing model are merged in the code here.


Running the examples
---------------------

To pick the simplest example first, one this repository has been downloaded, 
``cd`` into it, and ::

    python -m sqrt --num-batches 1000 sqrt/saved_state


Technical Note
................

Executing this command line will run the code in the ``sqrt`` 
module : specifically the command-line argument parser in 
the ``sqrt/__main__.py`` file.  Having the main entry point here is 
mostly a quirk of the Python module system - we wanted to keep the 
launching command as simple as possible.


Understanding the examples
---------------------------
The entry point of each example is ``main()`` function in ``EXAMPLE-NAME/__init__.py``.

We're currently working on getting better documentation coverage of the 
examples, and GitHub will helpfully display the contents of each 
folder's ``README`` file.

There's also certainly useful information in the ``blocks`` and ``fuel`` 
documentation :

* `Blocks documentation <http://blocks.readthedocs.org/>`_
* `Fuel documentation <http://fuel.readthedocs.org/>`_

Examples of projects using Blocks
---------------------------------
We host only standard and relatively compact examples here. For more
advanced and real-world examples see the following project, all of which heavily use 
Blocks:

* `Character-level RNN <https://github.com/johnarevalo/blocks-char-rnn>`_
* `DRAW model <https://github.com/jbornschein/draw>`_
* `Speech recognition <https://github.com/rizar/attention-lvcsr>`_
