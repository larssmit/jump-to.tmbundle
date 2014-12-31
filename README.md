# JumpTo

JumpTo is another CTags bundle for TextMate 2.

Current features:

⎇. : Jump to definition of anything selected/under the cursor (defined in your project). If multiple definitions exist you will have to select the proper file from a menu.

Based on the work of Mads Hartmann Jensen(mads379@gmail.com) at https://github.com/mads379/CTAGS-Improved.tmbundle.

# Requirements

The default ``ctags`` executable in OSX does not support recursive directory search (i.e. ``ctags -R``). To get a proper copy of ctags, use one of the following options:

* Using `Homebrew`_::

    brew install ctags

* Using `MacPorts`_::

    port install ctags

.. _`Homebrew`: http://mxcl.github.com/homebrew/
.. _`MacPorts`: http://www.macports.org/

Ensure that the ``PATH`` is updated so the correct version is run:

If ``which ctags`` doesn't point at ctags in ``/usr/local/bin``, make sure you add ``/usr/local/bin`` to your ``PATH`` ahead of the folder ``which ctags`` reported.

# How to install

Clone this repository into ~/Library/Application Support/Avian/Bundles:

	git clone https://github.com/larssmit/jump-to.tmbundle.git

JumpTo should appear under the "Bundles" menu item in TextMate 2.

# License

If not otherwise specified (see below), files in this repository fall under the following license:

	Permission to copy, use, modify, sell and distribute this
	software is granted. This software is provided "as is" without
	express or implied warranty, and with no claim as to its
	suitability for any purpose.

An exception is made for files in readable text which contain their own license information, or files where an accompanying file exists (in the same directory) with a “-license” suffix added to the base-name name of the original file, and an extension of txt, html, or similar. For example “tidy” is accompanied by “tidy-license.txt”.