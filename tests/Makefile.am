## Process this file with automake to produce Makefile.in

check_PROGRAMS = signon-glib-testsuite
dist_check_SCRIPTS = signon-glib-test.sh

signon_glib_testsuite_SOURCES = check_signon.c
signon_glib_testsuite_CPPFLAGS = \
	-I$(top_srcdir) \
	$(DEPS_CFLAGS) \
	$(CHECK_FLAGS)
signon_glib_testsuite_LDADD = \
	$(top_builddir)/libsignon-glib/libsignon-glib.la \
	$(CHECK_LIBS) \
	$(DEPS_LIBS) \
	-lpthread

TESTS = signon-glib-test.sh
