lib_LTLIBRARIES = shockwaveDeath.la

shockwaveDeath_la_SOURCES = shockwaveDeath.cpp
shockwaveDeath_la_CPPFLAGS = -I$(top_srcdir)/include
shockwaveDeath_la_LDFLAGS = -module -avoid-version -shared

AM_CPPFLAGS = $(CONF_CPPFLAGS)
AM_CFLAGS = $(CONF_CFLAGS)
AM_CXXFLAGS = $(CONF_CXXFLAGS)

EXTRA_DIST =			\
	README.txt		\
	shockwaveDeath.def	\
	shockwaveDeath.sln	\
	shockwaveDeath.vcxproj

MAINTAINERCLEANFILES =	\
	Makefile.in
