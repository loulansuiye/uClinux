## Process this file with automake to produce Makefile.in

#AUTOMAKE_OPTIONS        =  foreign

#ACLOCAL_M4 = $(top_srcdir)/config/aclocal.m4

EXTRA_DIST = cgi-demo.cgi.in piped-demo.pl.in shared-demo.pl.in \
	stripes.pl.in bigtops.pl.in minmax.pl.in 4charts.pl.in

EXPREFIX:=$(shell echo "@prefix@" | grep rrd >/dev/null || echo "rrdtool-@VERSION@/")
examplesdir = $(prefix)/$(EXPREFIX)examples
examples_SCRIPTS = cgi-demo.cgi piped-demo.pl shared-demo.pl \
	stripes.pl bigtops.pl minmax.pl 4charts.pl

