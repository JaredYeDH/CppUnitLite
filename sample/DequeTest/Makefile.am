AUTOMAKE_OPTIONS = foreign

AM_CPPFLAGS = -I$(top_srcdir)/include

bin_PROGRAMS = DequeTest
DequeTest_SOURCES = DequeTest.cpp \
		    Deque.cpp \
		    Deque.h
DequeTest_LDADD = $(top_builddir)/src/libCppUnitLite.a
