# The libraries to build
noinst_LIBRARIES = libdx-aw-base.a
noinst_HEADERS = dx-aw-base.h

# The files to add to the library and to the source distribution
libdx_aw_base_a_SOURCES = \
                         $(libdx_aw_base_a_HEADERS) \
                         dx-aw-base.c

if DEBUG
  AM_CFLAGS =-I$(top_srcdir)/src/lib -Wall -g -O3
else
  AM_CFLAGS =-I$(top_srcdir)/src/lib -Wall
endif