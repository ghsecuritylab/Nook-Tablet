noinst_LTLIBRARIES = libcompat.la
EXTRA_libcompat_la_SOURCES = hsearch_r.c

if ALSA_HSEARCH_R
libcompat_la_SOURCES = empty.c hsearch_r.c
else
libcompat_la_SOURCES = empty.c
endif
