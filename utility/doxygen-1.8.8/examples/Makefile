#
# This file was generated from Makefile.in on Thu Aug 21 16:22:33 CEST 2014
#

DOXYGEN   = /home/dimitri/doxygen/package/doxygen-1.8.8
TMAKEPATH = /home/dimitri/doxygen/package/doxygen-1.8.8/tmake/lib/linux-g++
ENV       = env TMAKEPATH="$(TMAKEPATH)"
TMAKE     = /home/dimitri/doxygen/package/doxygen-1.8.8/tmake/bin/tmake
MAKE      = /usr/bin/make
PYTHON    = /usr/bin/python3
PERL      = /usr/bin/perl
LEX       = /usr/bin/flex
RM        = rm -f
CP        = cp
VERSION   = 1.8.8
INSTALL   = /usr/local
INSTTOOL  = /usr/bin/install
DOXYDOCS  = ..
DOCDIR    = $(INSTALL)/share/doc/packages/doxygen
QTDIR     = /usr
HAVE_DOT  = /usr/bin/dot
DOXYGEN_BIN="$(DOXYGEN)/bin/doxygen"

all: class/html/index.html \
     define/html/index.html \
     enum/html/index.html \
     file/html/index.html \
     func/html/index.html \
     page/html/index.html \
     relates/html/index.html \
     author/html/index.html \
     par/html/index.html \
     overload/html/index.html \
     example/html/index.html \
     include/html/index.html \
     qtstyle/html/index.html \
     jdstyle/html/index.html \
     structcmd/html/index.html \
     autolink/html/index.html \
     restypedef/html/index.html \
     afterdoc/html/index.html \
     template/html/index.html \
     tag/html/index.html \
     group/html/index.html \
     diagrams/html/index.html \
     memgrp/html/index.html \
     docstring/html/index.html \
     pyexample/html/index.html \
     tclexample/html/index.html \
     mux/html/index.html \
     manual/html/index.html

# Disabled since it is broken :-(
#     dbusxml/html/index.html

clean:
	rm -rf  class define enum file func page relates author \
                par overload example include qtstyle jdstyle structcmd \
		autolink tag restypedef afterdoc template tag group diagrams \
		memgrp docstring pyexample mux manual dbusxml tclexample

class/html/index.html: class.h class.cfg
	$(DOXYGEN_BIN) class.cfg

define/html/index.html: define.h define.cfg
	$(DOXYGEN_BIN) define.cfg

enum/html/index.html: enum.h enum.cfg
	$(DOXYGEN_BIN) enum.cfg

file/html/index.html: file.h file.cfg
	$(DOXYGEN_BIN) file.cfg

func/html/index.html: func.h func.cfg
	$(DOXYGEN_BIN) func.cfg

page/html/index.html: page.doc page.cfg
	$(DOXYGEN_BIN) page.cfg

relates/html/index.html: relates.cpp relates.cfg
	$(DOXYGEN_BIN) relates.cfg

author/html/index.html: author.cpp author.cfg
	$(DOXYGEN_BIN) author.cfg

par/html/index.html: par.cpp par.cfg
	$(DOXYGEN_BIN) par.cfg

overload/html/index.html: overload.cpp overload.cfg
	$(DOXYGEN_BIN) overload.cfg

example/html/index.html: example.cpp example_test.cpp example.cfg
	$(DOXYGEN_BIN) example.cfg

include/html/index.html: include.cpp example_test.cpp include.cfg
	$(DOXYGEN_BIN) include.cfg

qtstyle/html/index.html: qtstyle.cpp qtstyle.cfg
	$(DOXYGEN_BIN) qtstyle.cfg

jdstyle/html/index.html: jdstyle.cpp jdstyle.cfg
	$(DOXYGEN_BIN) jdstyle.cfg

structcmd/html/index.html: structcmd.h structcmd.cfg
	$(DOXYGEN_BIN) structcmd.cfg

autolink/html/index.html: autolink.cpp autolink.cfg
	$(DOXYGEN_BIN) autolink.cfg

tag/html/index.html: tag.cpp tag.cfg example/html/index.html
	$(DOXYGEN_BIN) tag.cfg

restypedef/html/index.html: restypedef.cpp restypedef.cfg
	$(DOXYGEN_BIN) restypedef.cfg

afterdoc/html/index.html: afterdoc.h afterdoc.cfg
	$(DOXYGEN_BIN) afterdoc.cfg

template/html/index.html: templ.cpp templ.cfg
	$(DOXYGEN_BIN) templ.cfg

group/html/index.html: group.cpp group.cfg
	$(DOXYGEN_BIN) group.cfg

memgrp/html/index.html: memgrp.cpp memgrp.cfg
	$(DOXYGEN_BIN) memgrp.cfg

pyexample/html/index.html: pyexample.py pyexample.cfg
	$(DOXYGEN_BIN) pyexample.cfg

tclexample/html/index.html: tclexample.tcl tclexample.cfg
	$(DOXYGEN_BIN) tclexample.cfg

mux/html/index.html: mux.vhdl mux.cfg
	$(DOXYGEN_BIN) mux.cfg

manual/html/index.html: manual.c manual.cfg
	$(DOXYGEN_BIN) manual.cfg

docstring/html/index.html: docstring.py docstring.cfg
	$(DOXYGEN_BIN) docstring.cfg

#dbusxml/html/index.html: dbusxml.xml dbusxml.cfg
#	$(DOXYGEN_BIN) dbusxml.cfg

diagrams/html/index.html: diagrams_a.h diagrams_b.h diagrams_c.h diagrams_d.h diagrams_e.h diagrams.cfg
ifneq ($(HAVE_DOT),)
	$(DOXYGEN_BIN) diagrams.cfg
endif

