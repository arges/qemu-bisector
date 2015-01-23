qemu-bisector
=============

Bisect Harness for QEMU

Author: Chris J Arges <christopherarges@gmail.com>
License: MIT

This is something to make my life easier when I need to bisect qemu.

quick-start
===========

* Create disk that has a testcase that can be run from expect (use install-vm)
* Edit bisect-run compile to match how you want to compile
* Testcase must output something that is checkable
* Edit check value to match testcase output
* Edit testcase to match your paths and qemu commands
* Git bisect run it!
