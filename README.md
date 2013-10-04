qemu-bisector
=============

Author: Chris J Arges <christopherarges@gmail.com>
License: MIT

This is something to make my life easier when I need to bisect qemu.

quick-start
===========

1) Edit bisect-run compile to match how you want to compile
2) Create disk that has a testcase that can be run from expect
3) Testcase must output something that is checkable
4) Edit check value to match testcase output
5) Edit testcase to match your paths and qemu commands
6) Git bisect run it!
Bisect Harness for QEMU
