SUBDIRS = .

lib_LTLIBRARIES = libutrac.la


AM_CFLAGS = \
		-w -Wno-multichar -DUT_CHARMAPS_FILENAME='"/usr/share/utrac/charsets.dat"'
libutrac_includedir = $(includedir)/utrac
libutrac_include_HEADERS =	\
	debug.h			\
	ut_charset.h		\
	ut_error.h		\
	ut_text.h		\
	utrac.h			

libutrac_la_SOURCES = 		\
	ut_charset.c		\
	ut_conversion.c		\
	ut_loading.c		\
	ut_messages_en.c	\
	ut_recognition1.c	\
	ut_recognition2.c	\
	ut_utils.c		\
	utrac.c			\
	utrac_cmd.c

