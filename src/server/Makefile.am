
AM_CPPFLAGS = -I../../include -I.. -I../../3rdparty

lib_LTLIBRARIES = libhamserver.la

libhamserver_la_SOURCES = hamserver.c os.c

libhamserver_la_LDFLAGS = -version-info 0:0:0

libhamserver_la_LDFLAGS += $(top_builddir)/3rdparty/json/libjson.la \
                           $(top_builddir)/3rdparty/mongoose/libmongoose.la \
                           $(top_builddir)/src/protocol/libprotocol.la


