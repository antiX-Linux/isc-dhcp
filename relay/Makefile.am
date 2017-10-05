BINDLIBDIR = @BINDDIR@/lib

AM_CPPFLAGS = -DLOCALSTATEDIR='"@localstatedir@"'

sbin_PROGRAMS = dhcrelay
dhcrelay_SOURCES = dhcrelay.c
dhcrelay_LDADD = ../common/libdhcp.a ../omapip/libomapi.a \
		 -ldns-export -lisc-export
man_MANS = dhcrelay.8
EXTRA_DIST = $(man_MANS)

