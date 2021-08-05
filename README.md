odsset
======

This tool lets you set values in an ods or xlsx file from the command-line.

example
=======

./odsset --format=ods --output=output.ods input.ods 'Sheet1,1,5,111130'

In this example, the tool reads in input.ods, makes a change to "Sheet1" if it exists, and writes out to output.ods


license
=======

GNU General Public License as published by the Free Software Foundation;
version 2 only

See the LICENSE file

copyright
=========

This is a fork of the unoconv tool, copyright 2007-2010 dag wieers

