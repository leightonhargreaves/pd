#Copyright (C) 2007 L. Donnie Smith

include ../defs.mak

docfiles = Xmodmap wminput.list

DEST_DOC_DIR = $(ROOTDIR)$(docdir)

all:

install: $(DEST_DOC_DIR)
	install -m 644 $(docfiles) $(DEST_DOC_DIR)

$(DEST_DOC_DIR):
	install -d $(DEST_DOC_DIR)

uninstall:
	rm -rf $(DEST_DOC_DIR)

distclean:
	rm Makefile

.PHONY: all install uninstall distclean
