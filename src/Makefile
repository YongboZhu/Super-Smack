# Makefile.in generated automatically by automake 1.4 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# Copyright (C) 2000 MySQL AB & MySQL Finland AB & TCX DataKonsult AB
# 
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

# Process this file with automake to create Makefile.in


SHELL = /bin/sh

srcdir = .
top_srcdir = ..

prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/super-smack
pkglibdir = $(libdir)/super-smack
pkgincludedir = $(includedir)/super-smack

top_builddir = ..

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = automake
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
CC = gcc
CPP = gcc -E
CXX = g++
DATADIR = /var/smack-data
LEX = flex
LN_S = ln -s
MAKEINFO = makeinfo
MYSQL_INCLUDE = -I/usr/local/include/mysql
MYSQL_LIB = -L/usr/local/lib/mysql -lmysqlclient 
ORACLE_INCLUDE = 
ORACLE_LIB = 
PACKAGE = super-smack
PGSQL_INCLUDE = -I/usr/local/pgsql/include
PGSQL_LIB = -L/usr/local/pgsql/lib -lpq
SHELL = /bin/sh
SMACKS_DIR = /usr/share/smacks
VERSION = 1.1
YACC = bison -y

INCLUDES = -I/usr/local/include/mysql -I/usr/local/pgsql/include 

noinst_PROGRAMS = test-dictionary test-client test_tcp_client
bin_PROGRAMS = super-smack gen-data
test_dictionary_SOURCES = test-dictionary.cc 	dictionary.cc dictionary.h 	die.cc die.h 	smack.h libsmack.cc

test_tcp_client_SOURCES = test_tcp_client.cc tcp_client.cc tcp_client.h
test_client_SOURCES =  	test-client.cc 	client.cc client.h 	engines.cc engines.h 	die.cc die.h 	dictionary.cc dictionary.h 	query.cc query.h 	smack.h libsmack.cc 	mysql-client.cc mysql-client.h 	pg-client.cc pg-client.h 	ora-client.cc ora-client.h

test_client_LDADD = -L/usr/local/lib/mysql -lmysqlclient  -L/usr/local/pgsql/lib -lpq 

super_smack_SOURCES =  	super-smack.cc super-smack.h 	client.cc client.h 	engines.cc engines.h 	die.cc die.h         dictionary.cc dictionary.h 	super-smack-yacc.yy         super-smack-yacc.h 	super-smack-lex.ll 	query.cc query.h         parse.cc parse.h 	val.h smack.h libsmack.cc 	mysql-client.cc mysql-client.h 	pg-client.cc pg-client.h 	ora-client.cc ora-client.h 	tcp_client.h tcp_client.cc

super_smack_LDADD = -L/usr/local/lib/mysql -lmysqlclient  -L/usr/local/pgsql/lib -lpq 

gen_data_SOURCES = gen-data.cc die.cc die.h

# yacc needs to generate a y.tab.h
YFLAGS = -d

# extra files to delete with ``make clean''
CLEANFILES = super-smack-yacc.cc super-smack-yacc.h super-smack-lex.cc
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = ../config.h
CONFIG_CLEAN_FILES = 
PROGRAMS =  $(bin_PROGRAMS) $(noinst_PROGRAMS)


DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I..
CPPFLAGS = 
LDFLAGS = 
LIBS = -L/usr/local/pgsql/lib -L/usr/local/lib/mysql -lcrypt -lz  
super_smack_OBJECTS =  super-smack.o client.o engines.o die.o \
dictionary.o super-smack-yacc.o super-smack-lex.o query.o parse.o \
libsmack.o mysql-client.o pg-client.o ora-client.o tcp_client.o
super_smack_DEPENDENCIES = 
super_smack_LDFLAGS = 
gen_data_OBJECTS =  gen-data.o die.o
gen_data_LDADD = $(LDADD)
gen_data_DEPENDENCIES = 
gen_data_LDFLAGS = 
test_dictionary_OBJECTS =  test-dictionary.o dictionary.o die.o \
libsmack.o
test_dictionary_LDADD = $(LDADD)
test_dictionary_DEPENDENCIES = 
test_dictionary_LDFLAGS = 
test_client_OBJECTS =  test-client.o client.o engines.o die.o \
dictionary.o query.o libsmack.o mysql-client.o pg-client.o ora-client.o
test_client_DEPENDENCIES = 
test_client_LDFLAGS = 
test_tcp_client_OBJECTS =  test_tcp_client.o tcp_client.o
test_tcp_client_LDADD = $(LDADD)
test_tcp_client_DEPENDENCIES = 
test_tcp_client_LDFLAGS = 
CXXFLAGS = -g -O2
CXXCOMPILE = $(CXX) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(LDFLAGS) -o $@
LEX_OUTPUT_ROOT = lex.yy
LEXLIB = -lfl
CFLAGS = -g -O2
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(LDFLAGS) -o $@
DIST_COMMON =  Makefile.am Makefile.in super-smack-lex.cc \
super-smack-yacc.cc


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
SOURCES = $(super_smack_SOURCES) $(gen_data_SOURCES) $(test_dictionary_SOURCES) $(test_client_SOURCES) $(test_tcp_client_SOURCES)
OBJECTS = $(super_smack_OBJECTS) $(gen_data_OBJECTS) $(test_dictionary_OBJECTS) $(test_client_OBJECTS) $(test_tcp_client_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .cc .ll .o .s .yy
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu --include-deps src/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


mostlyclean-binPROGRAMS:

clean-binPROGRAMS:
	-test -z "$(bin_PROGRAMS)" || rm -f $(bin_PROGRAMS)

distclean-binPROGRAMS:

maintainer-clean-binPROGRAMS:

install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(bindir)
	@list='$(bin_PROGRAMS)'; for p in $$list; do \
	  if test -f $$p; then \
	    echo "  $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`"; \
	     $(INSTALL_PROGRAM) $$p $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	  else :; fi; \
	done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	list='$(bin_PROGRAMS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(bindir)/`echo $$p|sed 's/$(EXEEXT)$$//'|sed '$(transform)'|sed 's/$$/$(EXEEXT)/'`; \
	done

mostlyclean-noinstPROGRAMS:

clean-noinstPROGRAMS:
	-test -z "$(noinst_PROGRAMS)" || rm -f $(noinst_PROGRAMS)

distclean-noinstPROGRAMS:

maintainer-clean-noinstPROGRAMS:

.c.o:
	$(COMPILE) -c $<

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

super-smack: $(super_smack_OBJECTS) $(super_smack_DEPENDENCIES)
	@rm -f super-smack
	$(CXXLINK) $(super_smack_LDFLAGS) $(super_smack_OBJECTS) $(super_smack_LDADD) $(LIBS)

gen-data: $(gen_data_OBJECTS) $(gen_data_DEPENDENCIES)
	@rm -f gen-data
	$(CXXLINK) $(gen_data_LDFLAGS) $(gen_data_OBJECTS) $(gen_data_LDADD) $(LIBS)

test-dictionary: $(test_dictionary_OBJECTS) $(test_dictionary_DEPENDENCIES)
	@rm -f test-dictionary
	$(CXXLINK) $(test_dictionary_LDFLAGS) $(test_dictionary_OBJECTS) $(test_dictionary_LDADD) $(LIBS)

test-client: $(test_client_OBJECTS) $(test_client_DEPENDENCIES)
	@rm -f test-client
	$(CXXLINK) $(test_client_LDFLAGS) $(test_client_OBJECTS) $(test_client_LDADD) $(LIBS)

test_tcp_client: $(test_tcp_client_OBJECTS) $(test_tcp_client_DEPENDENCIES)
	@rm -f test_tcp_client
	$(CXXLINK) $(test_tcp_client_LDFLAGS) $(test_tcp_client_OBJECTS) $(test_tcp_client_LDADD) $(LIBS)
.cc.o:
	$(CXXCOMPILE) -c $<
.ll.cc:
	$(LEX) $(AM_LFLAGS) $(LFLAGS) $< && mv $(LEX_OUTPUT_ROOT).c $@
.yy.cc:
	$(YACC) $(AM_YFLAGS) $(YFLAGS) $< && mv y.tab.c $*.cc
	if test -f y.tab.h; then \
	if cmp -s y.tab.h $*.h; then rm -f y.tab.h; else mv y.tab.h $*.h; fi; \
	else :; fi
super-smack-yacc.hh: super-smack-yacc.cc


tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags $(ETAGS_ARGS) $$tags  $$unique $(LISP) -o $$here/TAGS)

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = src

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
client.o: client.cc ../config.h client.h dictionary.h query.h val.h \
	die.h
dictionary.o: dictionary.cc ../config.h dictionary.h smack.h
die.o: die.cc ../config.h die.h
engines.o: engines.cc ../config.h engines.h client.h dictionary.h \
	query.h val.h
gen-data.o: gen-data.cc ../config.h die.h
libsmack.o: libsmack.cc ../config.h smack.h die.h
mysql-client.o: mysql-client.cc ../config.h client.h dictionary.h \
	query.h val.h engines.h mysql-client.h die.h
ora-client.o: ora-client.cc ../config.h
parse.o: parse.cc ../config.h die.h smack.h engines.h client.h \
	dictionary.h query.h val.h parse.h
pg-client.o: pg-client.cc ../config.h
query.o: query.cc ../config.h query.h die.h client.h dictionary.h val.h
super-smack-lex.o: super-smack-lex.cc query.h ../config.h parse.h \
	client.h dictionary.h val.h super-smack-yacc.h
super-smack-yacc.o: super-smack-yacc.cc ../config.h die.h query.h \
	client.h dictionary.h val.h parse.h
super-smack.o: super-smack.cc ../config.h die.h query.h client.h \
	dictionary.h val.h engines.h parse.h super-smack.h
tcp_client.o: tcp_client.cc ../config.h tcp_client.h
test-client.o: test-client.cc ../config.h client.h dictionary.h query.h \
	val.h engines.h die.h
test-dictionary.o: test-dictionary.cc ../config.h dictionary.h
test_tcp_client.o: test_tcp_client.cc tcp_client.h

info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am: install-binPROGRAMS
install-exec: install-exec-am

install-data-am:
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-binPROGRAMS
uninstall: uninstall-am
all-am: Makefile $(PROGRAMS)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(bindir)


mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
	-test -z "super-smack-lexllsuper-smack-yacchhsuper-smack-yacccc" || rm -f super-smack-lexll super-smack-yacchh super-smack-yacccc
mostlyclean-am:  mostlyclean-binPROGRAMS mostlyclean-noinstPROGRAMS \
		mostlyclean-compile mostlyclean-tags \
		mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-binPROGRAMS clean-noinstPROGRAMS clean-compile \
		clean-tags clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-binPROGRAMS distclean-noinstPROGRAMS \
		distclean-compile distclean-tags distclean-generic \
		clean-am

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-binPROGRAMS \
		maintainer-clean-noinstPROGRAMS \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: mostlyclean-binPROGRAMS distclean-binPROGRAMS clean-binPROGRAMS \
maintainer-clean-binPROGRAMS uninstall-binPROGRAMS install-binPROGRAMS \
mostlyclean-noinstPROGRAMS distclean-noinstPROGRAMS \
clean-noinstPROGRAMS maintainer-clean-noinstPROGRAMS \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile tags mostlyclean-tags distclean-tags \
clean-tags maintainer-clean-tags distdir info-am info dvi-am dvi check \
check-am installcheck-am installcheck install-exec-am install-exec \
install-data-am install-data install-am install uninstall-am uninstall \
all-redirect all-am all installdirs mostlyclean-generic \
distclean-generic clean-generic maintainer-clean-generic clean \
mostlyclean distclean maintainer-clean


# Don't update the files from bitkeeper
%::SCCS/s.%

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
