lib_LTLIBRARIES = autoFlagReset.la

autoFlagReset_la_SOURCES = autoFlagReset.cpp
autoFlagReset_la_CPPFLAGS = -I$(top_srcdir)/include
autoFlagReset_la_LDFLAGS = -module -avoid-version -shared

AM_CPPFLAGS = $(CONF_CPPFLAGS)
AM_CFLAGS = $(CONF_CFLAGS)
AM_CXXFLAGS = $(CONF_CXXFLAGS)

EXTRA_DIST = \
	README.txt \
	autoFlagReset.def \
	autoFlagReset.sln \
	autoFlagReset.vcxproj

MAINTAINERCLEANFILES =	\
	Makefile.in
