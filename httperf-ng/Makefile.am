## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src 

httperf_ngdocdir = ${prefix}/doc/httperf_ng
httperf_ngdoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(httperf_ngdoc_DATA)


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(httperf_ngdocdir)
