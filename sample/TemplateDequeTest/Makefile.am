AUTOMAKE_OPTIONS=foreign

AM_CPPFLAGS=-I$(top_srcdir)/include

bin_PROGRAMS = TemplateDequeTest
TemplateDequeTest_SOURCES = DequeTest.cpp \
			    Deque.cpp \
			    Deque.h
TemplateDequeTest_LDADD = $(top_builddir)/src/libCppUnitLite.a
