AUTOMAKE_OPTIONS=foreign

SUBDIRS = src \
	  sample/TestHarness \
	  sample/DequeTest \
	  sample/TemplateDequeTest \
	  sample/StackTest

EXTRA_DIST = BUGS autogen.sh \
	     lib/.gitignore \
	     bin/.gitignore

dist-hook:
	cp -dpR $(top_srcdir)/build $(distdir)/build
