# tutorial of autotools

[Reference](http://markuskimius.wikidot.com/programming:tut:autotools)

# summary

* Create source code

* run "autoscan" to generate "configure.scan"

* rename "configure.scan" to "configure.ac"

* run "autoheader" to generate "configure.h.in"

* make your source code portable by looking at config.h.in. add some #ifdef to you code and include config.h

* create "Makefile.am"

* run "automaek"

* Fix errors and run "automake" again

* run "aclocal"

* run "autoconf"

* run "./configure" "make" "make install"